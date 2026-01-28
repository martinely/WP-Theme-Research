# DESIGN TOKENS + COMPONENTS — AI Agency Theme (3 Homes)

Goal: One design system, three homepage variants (H1 agency, H2 micro-SaaS, H3 trainers).
Builder target: Elementor + Pro (template-friendly, no custom “magic”).

## A) Design tokens (global)

### Layout
- Desktop canvas: 1440w
- Grid: 12 cols, container 1200 centered, gutter 24
- Section vertical padding: 88–112 (hero can be larger)
- Card gaps: 16–24
- Max content widths:
  - Body text: 640–720
  - Narrow panels: 860–960

### Type scale (suggested)
- H1: 52–64 / tight line-height
- H2: 36–44
- H3: 24–28
- Body: 16–18
- Small / meta: 12–14
- Buttons: 14–16 (medium weight)

### Radii & shadows
- Card radius: 16
- Panel/modal radius: 20
- Buttons: 999 (pill) OR 14–16 (soft rounded) — pick one and keep consistent
- Shadow: very soft (1–2 layers), no heavy drop shadows

### Colors (system, not specific hex)
- Base background: warm-neutral or cool-neutral (choose one family)
- Surface: slightly elevated (cards/panels)
- Text: strong contrast
- Accent: 1 primary accent + 1 optional secondary accent (used sparingly)
- Status: success/warn/error for badges (subtle)

### Motion
- Micro-animations only: hover lift 2–4px, opacity fades, underline transitions
- Avoid “scroll-jacking” or excessive animation; performance first

### Icons/Illustrations
- Avoid generic AI clipart
- Use minimal line icons OR abstract technical patterns (consistent style)

---

## B) Global components (shared across all homes)

### 1) Header (sticky)
- Left: logo
- Middle: 4–6 nav items (supports 1-level dropdown)
- Right: primary CTA button
- Optional: “Sign in” link (H2 only)
- Mobile not required in current scope, but header must be structurally adaptable

### 2) Hero (3 variants)
Common fields:
- Eyebrow (optional)
- H1 + subhead
- Primary CTA + secondary CTA
- Proof chips (logos/metrics/badges slot)
Variant-specific:
- H1: outcomes-led + discovery call
- H2: product value + start free
- H3: training outcomes + explore programs

### 3) Card grid system (reusable)
- Supports 3–5 cards per row (responsive later)
- Card fields: icon/mark, title, 1–2 lines body, optional link
Used as:
- H1 capabilities
- H2 features / use-cases
- H3 programs / tracks

### 4) Proof / trust strip (3 modes)
Mode A: client logo wall
Mode B: metrics bar (e.g., “hours saved”, “ROI” placeholders)
Mode C: compliance/ratings badges (H2)
Rule: any strong claim should have a nearby proof slot.

### 5) CTA band (reusable)
- Short headline + 1 sentence
- Primary CTA button
- Optional: embedded form OR “book” placeholder
- Background: subtle accent surface/pattern

### 6) Form module (reusable)
- Agency/Training enquiry: name, email, company, message (+ optional team size)
- SaaS lead: email-first + SSO buttons placeholder (optional)
- Keep as simple form—no fake scheduling UI

### 7) Footer (reusable)
- 3–4 columns links
- Contact info block
- Legal links (privacy/terms)
- Optional: security/status links (H2)

---

## C) Home-specific components

### Home 1 (Agency)
- Methodology stepper (5 steps)
- Case study teaser cards (2–3)
- Industries / use-cases mini grid (optional)
- “Outcomes” metric strip (optional)

### Home 2 (Micro-SaaS)
- Integrations row (logo strip)
- Security/Trust bar (SOC2/GDPR/HIPAA placeholders)
- Pricing table (2–4 plans + monthly/annual toggle visual)
- Use-case grid (personas/teams)
- Testimonial/ratings strip (lightweight)

### Home 3 (Trainers/Consultants)
- Programs list (3 cards)
- Curriculum modules (tabs/accordion)
- Instructor bios (2–4)
- Outcomes panel (learner counts/ROI placeholders)
- Pricing optional:
  - either “Request a quote” panel
  - or subscription tiers (if applicable)

---

## D) Elementor template mapping (minimum viable)

Global:
- Global header template
- Global footer template
- Section templates: Hero variants (3), Card grid, Proof strip (3 modes), CTA band, Form module

Home pages:
- Home 1 template (H1)
- Home 2 template (H2)
- Home 3 template (H3)

Inner pages (next phase, not in this checklist):
- Services/Capabilities index + single
- Case studies index + single
- Pricing page (H2)
- Program/Course index + single (H3)
- Contact / Book

---

## E) Content model (keep simple)
- Don’t force CPTs unless needed.
Recommended (optional):
- Case Studies (H1)
- Programs/Courses (H3)
- Blog/Resources (global)
Everything else can be repeater fields within Elementor templates.
