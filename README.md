name: Research QA

on:
  workflow_dispatch:
  pull_request:
    branches: [ "main" ]
  push:
    branches: [ "main" ]

jobs:
  validate-research-structure:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Show repo tree (top)
        run: |
          echo "=== Repo root ==="
          ls -la
          echo "=== .github/workflows ==="
          ls -la .github/workflows || true
          echo "=== niches (if exists) ==="
          ls -la niches || true

      - name: Validate required paths (counseling example)
        run: |
          set -e

          REQUIRED=(
            "niches/counseling/00_results/00_RESULTS_working.md"
            "niches/counseling/research/TF-01_Screening.md"
            "niches/counseling/research/TF-02_Winner_Deep_Dive.md"
            "niches/counseling/research/REAL-SUM-CLEAN.md"
            "niches/counseling/research/SYN-01_Blueprint.md"
            "niches/counseling/prompts/FIGMA-01_prompt.txt"
            "niches/counseling/prompts/INNER-00_about_prompt.txt"
            "niches/counseling/prompts/INNER-01_services_prompt.txt"
            "niches/counseling/prompts/INNER-02_service_single_prompt.txt"
            "niches/counseling/appendices/Appendix_INNER_Master_Subpages.md"
            "niches/counseling/sources/MASTER_SAMPLESET.txt"
            "niches/counseling/sources/FALLBACK_SET.txt"
            "niches/counseling/sources/URL_POOL.txt"
          )

          echo "Checking required files..."
          MISSING=0
          for p in "${REQUIRED[@]}"; do
            if [ ! -f "$p" ]; then
              echo "::error file=$p::Missing required file: $p"
              MISSING=1
            else
              echo "OK: $p"
            fi
          done

          if [ "$MISSING" -eq 1 ]; then
            echo "One or more required files are missing."
            exit 1
          fi

          echo "All required files are present."

      - name: Optional: show counseling folder tree
        run: |
          if command -v tree >/dev/null 2>&1; then
            tree -a niches/counseling || true
          else
            echo "tree not installed; using find:"
            find niches/counseling -maxdepth 4 -type f || true
          fi
