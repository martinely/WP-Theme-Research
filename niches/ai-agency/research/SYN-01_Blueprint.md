# SYN-01_Blueprint (compact, audit-ready) — AI Agency Theme (3 Homes)

## 0) SCOPE
One premium WordPress theme with **one shared design system** and **three distinct homepages**:
- **HOME 01 (Primary): AI Automation / Integration Agency**
- **HOME 02: AI micro-SaaS products**
- **HOME 03: AI trainers / consultants**

**Rule:** same global tokens + shared components, but **distinct hero framing, CTA logic, and section order per home**.

---

## 1) NON-NEGOTIABLE RULES
- **Facts-first:** no invented metrics, clients, awards, certifications, numbers.
- **Allowed placeholders only:** “X+”, “From $X”, “X sessions”, “Team size: X–Y”, “Timeline: X–Y weeks”.
- **Primary CTAs (must):**
  - H1: **“Book a discovery call”** (external scheduler modal preferred; link-out allowed)
  - H2: **“Try a product” / “Start free”**
  - H3: **“Book a consultation”** (external scheduler modal preferred; link-out allowed)
- **1 primary CTA per home** (one secondary max).
- **Avoid AI clichés:** robots, glowing brains, generic “AI” stock. Prefer abstract systems, real teams, dashboards, integrations.
- Elementor + Elementor Pro only (assumption for templateability). No “magic” features.

---

## 2) TONE DECISION (grounded in our REAL + TF direction)
Baseline across all homes:
- **Confident, modern, high-end, tech-forward but warm** (not sterile).
- **Outcome-oriented, plain language**, minimal buzzwords.
- Trust is built via **process clarity + proof slots** (logos, testimonials, case snippets, security badges) rather than bold numeric claims.

Home-specific tone:
- **H1 (Agency):** consultative, delivery-focused, credible; emphasize reliability + security posture + measurable outcomes (with placeholders).
- **H2 (micro-SaaS):** product-led clarity; benefit-first; trust via privacy/security language + integrations + ratings placeholders.
- **H3 (Trainers):** authority + curriculum clarity; adoption-focused; credibility via instructors + program structure + outcomes framing.

---

## 3) SHARED DESIGN SYSTEM (must feel like one theme)
Use the same across all homes:
- Typography scale, spacing, grid, radii, shadows, icon style
- Card system (service/feature/program), proof strip, testimonial card, CTA band, footer
- Motion language (subtle + consistent), hover/focus states, accessibility conventions

### Shared “page grammar” (common blocks)
1) Hero (headline + subhead + 1–2 CTAs)
2) Proof/Trust (logos/badges/metrics chips)
3) Offer summary (services/features/programs)
4) How it works / Method (stepper or structured narrative)
5) Proof deepener (case studies, testimonials, outcomes)
6) Conversion close (CTA band + form / booking)
7) Footer (privacy/terms/security links as appropriate)

---

## 4) GLOBAL IA (shared navigation + system)
### Header (sticky)
- Nav baseline: **Services, Use Cases, Process, Industries, Proof, Pricing, Resources, Contact**
- Utility link: **Security & compliance** (can be footer instead)
- Primary CTA button label is **home-specific** (H1/H2/H3)

### Footer
- Sitemap links, Privacy/Terms, Contact details, Social

---

## 5) SECTION ORDER — PER HOME (LOCKED)
### HOME 01 (Agency) — section order
1) Hero (H1 + subhead + proof chips + 2 CTAs)
2) Trusted by / logos (optional)
3) **#use-cases Automation examples** (high priority)
4) **#services What we do** (4–6 cards)
5) **#process How we work** (4-step timeline)
6) Industries grid
7) **#proof Proof & credibility** (case teasers + testimonials + stack mini-grid)
8) Pricing (tiers + scope microcopy)
9) FAQ
10) **#contact Booking + fallback form**
11) Footer

### HOME 02 (micro-SaaS) — section order
1) Hero (product-led value prop + 2 CTAs)
2) Product suite (3–6 product cards)
3) Integrations
4) Use cases (chips grouped by team)
5) How it works (3 steps + data/privacy link)
6) Security/Trust bar + testimonials/ratings
7) Pricing (Free/Pro/Team + toggle; Enterprise optional)
8) FAQ
9) CTA band
10) Footer

### HOME 03 (Trainers) — section order
1) Hero (adoption + safety + 2 CTAs)
2) Programs (3 cards)
3) Delivery formats
4) **#curriculum Curriculum preview** (accordion/grid)
5) **#team Instructors**
6) For Teams (procurement-friendly box)
7) Resources
8) FAQ
9) Contact/booking
10) Footer

---

## 6) ENTERPRISE-ONLY PATTERNS TO AVOID (keep optional)
- Mega menus, deep multi-level nav, region selectors
- Heavy “trust center” / long compliance sections as mandatory homepage content
- Huge resource libraries / careers portals as core IA
- Over-complex pricing with many tiers or rigid enterprise controls

---

## 7) CONTENT MODEL (editable objects)
Prefer repeaters / flexible fields over hard CPTs unless reuse is obvious.

### Global editable objects (shared)
- Proof chips (text + optional icon)
- Logos strip (logo + label)
- Testimonials (quote + name + role + company)
- CTA band (headline + subhead + button + optional small note)

### H1 objects
- Services/capabilities (title + 1–2 lines + link)
- Use-case cards (Inputs / Automates / Result)
- Process steps (label + 1 line)
- Case studies (Problem / Approach / Outcome line + link)

### H2 objects
- Product cards (name + promise + “best for” tags + bullets + CTA)
- Features (title + 1 line)
- Integrations (logo + name)
- Plans (name + price placeholder + bullets + CTA)
- Security badges (badge + label)
- Use-case chips (team grouping)

### H3 objects
- Programs (title + audience + duration placeholder + outcomes + CTA)
- Modules (label + bullets)
- Instructors (name + credential line + focus + link placeholder)
- Role/industry tracks (simple segmented grid, optional)

---

## 8) COPY RULES (premium tone)
- One-line headlines; concrete verbs; minimal filler.
- Avoid vague superlatives (“best”, “revolutionary”) unless a nearby proof slot exists.
- Every claim should have an adjacent proof slot (logo/quote/badge/case snippet).

---

# APPENDIX — CONTENT PACKS (ready-to-use copy)

## HOME 01 — CONTENT PACK (Agency)

### Hero
H1: Automate work. Integrate systems. Ship faster.  
Subhead: We design and deploy AI + workflow automations across your tools—reliably, securely, and with measurable outcomes.  
Primary CTA: Book a discovery call  
Secondary CTA: View automation examples  
Proof chips:
- Zapier / Make / n8n
- OpenAI / Anthropic
- HubSpot / Salesforce
- Slack / Google Workspace
Micro trust line (optional): Built for production, not demos.

### Services cards (4–6)
- AI workflow automation — Reduce manual handoffs and busywork across teams.
- System integrations & API glue — Connect tools cleanly, with reliable data flow.
- Internal tools & agents — Assist teams with retrieval, drafting, triage, and routing.
- Data pipelines & enrichment — Normalize, enrich, and sync data where it matters.
- Support & monitoring — Keep automations healthy with observability + iteration.

### Use-case cards (schema + examples)
Card format: Title + Tags + Inputs / Automates / Result

1) Lead intake → enrichment → routing  
Inputs: web forms, email, CRM  
Automates: enrichment, dedupe, assignment, alerts  
Result: faster follow-up, cleaner pipeline

2) Support triage → summarization → ticket creation  
Inputs: inbox, chat, helpdesk  
Automates: summarise, classify, create ticket, escalate  
Result: quicker response, consistent triage

3) Finance ops → invoice matching → alerts  
Inputs: invoices, PO data, accounting tool  
Automates: match, flag exceptions, notify approver  
Result: fewer exceptions missed

4) Sales calls → notes → follow-ups → tasks  
Inputs: meeting recordings, CRM  
Automates: notes, action items, CRM updates  
Result: better follow-through

5) Recruiting → screening → scheduling  
Inputs: applications, calendar  
Automates: screen, shortlist, schedule, reminders  
Result: less admin overhead

6) Knowledge base → Q&A bot → escalation  
Inputs: docs, wiki, tickets  
Automates: answer drafts, cite sources, escalate when needed  
Result: faster internal answers

### Process (4 steps)
1) Discovery & success criteria — define workflows, constraints, and “done”.  
2) Map workflows + data access — systems, permissions, risks, edge cases.  
3) Build + test + security review — staged rollout, validation, QA.  
4) Launch + monitor + iterate — observability, tweaks, ongoing support.  
Microcopy: Prefer to talk first? (phone placeholder)

### Proof section copy (templates)
Case study card structure:
- Problem:
- Approach:
- Outcome: (placeholders ok)

Testimonials (2–3):
- “Short quote about reliability and delivery.” — Name, Role (Company)

Stack mini-grid label: Our stack (tools & platforms we ship with)

### Pricing tiers (no real numbers)
- Starter automation — for one workflow / one team.
- Growth systems — multiple workflows + integrations + reporting.
- Enterprise program — multi-team rollout + governance + support.  
Microcopy: Scope varies by systems and access.

### FAQ (6–8)
- What access do you need to start?
- Do you build on our existing tools or bring your own stack?
- How do you handle security and sensitive data?
- Who owns the workflows, code, and documentation?
- What happens after launch (support/monitoring)?
- Can you work with partial access or sandbox environments?
- Do you support on-prem or private deployments? (optional)

---

## HOME 02 — CONTENT PACK (micro-SaaS)

### Hero
H1: Small AI tools that remove daily friction.  
Subhead: A suite of focused micro-SaaS products—meeting notes, workflow assistants, and automation add-ons that plug into your stack.  
Primary CTA: Try a product  
Secondary CTA: See integrations

### Product suite (example cards)
- Meeting Notes  
Promise: Turn meetings into clean notes, decisions, and tasks.  
Best for: Sales, Support, Managers  
Bullets: summaries • action items • follow-ups • exports  
CTA: View product

- Inbox Triage  
Promise: Classify requests and draft replies faster.  
Best for: Ops, Support  
Bullets: routing • templates • escalation • audit trail  
CTA: View product

- CRM Assistant  
Promise: Keep CRM updated without manual entry.  
Best for: Sales teams  
Bullets: call notes • field updates • reminders • hygiene checks  
CTA: View product

### Integrations
Label: Connect in minutes.  
Text: Works with your meeting tools, chat, and CRMs (integration grid).

### How it works (3 steps)
1) Connect  
2) Configure  
3) Run  
Link text: Data & privacy

### Pricing (placeholders)
Plans: Free / Pro / Team (+ Enterprise optional “Contact sales”)  
Toggle: Monthly / Annual (visual)  
Microcopy: Cancel anytime. Export your data.

### FAQ (6–8)
- What data do you store?
- Do you train models on our content?
- Can we export notes and tasks?
- Does it work with X tool?
- How does billing work?
- How do we cancel or downgrade?

---

## HOME 03 — CONTENT PACK (Trainers / Consultants)

### Hero
H1: Train your team to use AI—safely and effectively.  
Subhead: Hands-on workshops and consulting that translate tools into real workflows, policies, and measurable adoption.  
Primary CTA: Book a consultation  
Secondary CTA: View programs

### Programs (3 cards)
- AI Fundamentals for Teams  
Audience: cross-functional teams  
Outcomes: shared language, safe usage patterns, internal playbooks  
Format: workshop + exercises  
Duration: X sessions  
CTA: Get details

- Workflow Automation Bootcamp  
Audience: ops, RevOps, product, IT  
Outcomes: automate core workflows, governance basics, rollout plan  
Format: bootcamp + templates  
Duration: X weeks  
CTA: Get details

- Prompting + Evaluation for Business  
Audience: analysts, marketing, support  
Outcomes: prompt patterns, evaluation rubrics, quality control  
Format: hands-on lab  
Duration: X sessions  
CTA: Get details

### Delivery formats
In-person / Remote / Hybrid  
Team cohorts + office hours + async materials

### Curriculum preview (#curriculum)
- Foundations: models, limits, safety  
- Prompt patterns: structure, constraints, iteration  
- Workflow integration: tools, data, approvals  
- Evaluation: QA, rubrics, hallucination handling  
- Governance: policies, roles, escalation  
- Capstone: real workflow prototype

### Instructors (#team)
2–6 cards: Name / Role / Expertise / LinkedIn placeholder / Short credential line

### For Teams (procurement-friendly box)
- SOW-ready scope options
- Privacy options (placeholders)
- Enablement materials + internal rollout support

### Resources
Guides, checklists, policy templates (teasers)

### FAQ
- Prerequisites?
- Tools supported?
- Recordings and materials?
- Policy / governance coverage?
- Customisation for industry?
- How to measure adoption? (no numbers)
