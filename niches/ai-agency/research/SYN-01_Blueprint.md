SYN-01 (compact, audit-ready) — структура

## Executive stance (one-page) — AI Agency Theme (3 Homes)

### What we’re building
One premium WordPress theme with **one shared design system** and **three distinct homepages**:
- **Home 1 (Primary): AI Automation / Integration Agency**
- **Home 2: AI micro-SaaS products**
- **Home 3: AI trainers / consultants**

**Rule:** same components + tokens, but **distinct hero framing, CTA logic, and section order per home**.

---

### Shared design system (must feel like one theme)
Use the same:
- Typography scale, spacing, grid, radii, shadows, icon style
- Card system (feature/service/program cards), proof strip, testimonial card, CTA band, footer
- Motion language (subtle, consistent), hover/focus states, accessibility conventions

**Shared page grammar (common blocks across homes):**
1) Hero (headline + subhead + 1–2 CTAs)  
2) Proof/Trust (logos/badges/metrics chips)  
3) Offer summary (services/features/programs grid)  
4) “How it works” / Method / Workflow (stepper or structured narrative)  
5) Proof deepener (case studies, testimonials, outcomes)  
6) Conversion close (CTA band + form / booking)  
7) Footer (legal / privacy / terms as appropriate)

---

### What must differ per home (non-negotiable)
#### Home 1 — AI Automation / Integration Agency (Primary)
**Positioning:** outcomes + delivery confidence (automation, integration, agents, ROI).  
**Primary CTA:** contact / book discovery (lead capture).  
**Section order priority:** Proof early → Services early → Method → Case studies.  
**Pricing:** not emphasized; avoid plan tables by default.

**H1-specific components:**
- Capabilities / Services cards (3–6)
- Methodology stepper (3–6 steps)
- Case study teaser cards (2–6)
- Outcomes strip (metric chips, optional)

#### Home 2 — AI micro-SaaS products
**Positioning:** product value proposition (what it does + why better).  
**Primary CTA:** start free / sign up.  
**Secondary CTA:** request demo / contact sales.  
**Section order priority:** Features → Integrations → Trust/Security → Pricing → Proof.  
**Pricing:** standard (2–4 plans); enterprise as “Contact sales”.

**H2-specific components:**
- Feature stacks (rows) + feature grid
- Integrations row (logo strip)
- Security/Trust bar (badges)
- Pricing table (toggle optional)

#### Home 3 — AI trainers / consultants
**Positioning:** skill uplift + adoption + executive enablement.  
**Primary CTA:** explore programs / book briefing / enroll.  
**Section order priority:** Programs → Curriculum/modules → Instructors → Outcomes → CTA.  
**Pricing:** optional; many require consultation; allow both modes.

**H3-specific components:**
- Program cards (bootcamps/workshops/courses)
- Curriculum timeline / module list
- Instructor bios block
- Role/industry tracks (simple segmented grid, optional)

---

### Enterprise-only patterns to avoid (keep optional)
- Mega menus, deep multi-level nav, region selectors
- Heavy “trust center” / long compliance sections as mandatory homepage content
- Huge resource libraries / careers portals as core IA
- Over-complex pricing with many tiers or rigid enterprise controls

---

### Content model (what needs to be editable cleanly)
Prefer flexible repeaters over hard CPTs unless reuse is obvious.

**Global (shared) editable objects:**
- Proof chips (text + optional icon)
- Logos strip (logo + label)
- Testimonials (quote + name + role + company)
- CTA band (headline + subhead + button + optional small note)

**Home 1 objects:**
- Services/capabilities (title + 1–2 lines + link)
- Process steps (label + 1 line)
- Case studies (headline + outcome line + link)

**Home 2 objects:**
- Features (title + 1 line)
- Integrations (logo + name)
- Plans (plan name + price + bullets + CTA)
- Security badges (badge + label)

**Home 3 objects:**
- Programs (title + audience + duration + outcomes + CTA)
- Modules (label + bullets)
- Instructors (name + credential line + focus)

---

### Design outcome goal
A single theme that can launch as:
- a premium agency site (Home 1),
- a SaaS landing + pricing funnel (Home 2),
- a training/education offer (Home 3),

without feeling like three unrelated templates.


0) Non-negotiables
	•	One design system, 3 home variants (H1/H2/H3)
	•	Distinct: Hero, section order, proof type, CTA destination
	•	Avoid: mega menus, enterprise portals, deep compliance hubs (освен като линк)

1) Shared design principles (за да не стане “3 темплейта”)
	•	One typography scale, one spacing system, one card system
	•	One “proof language” component, но с различни съдържания:
	•	H1: outcomes + logos
	•	H2: compliance + ratings + integrations
	•	H3: instructor credibility + learner/corp proof + outcomes
	•	1 primary CTA per home, 1 secondary max

2) Home blueprints (по 8–10 секции макс)

За всеки Home описваме:
	•	Goal (1 sentence)
	•	Hero: structure + CTA labels + “what to show”
	•	Section order (numbered)
	•	Proof pack (какъв тип доказателства)
	•	Content objects (какви “карти” и списъци)
	•	Do / Don’t

H1 — AI Automation / Integration Agency (primary)
	1.	Hero (promise + CTA: Book/Contact) + 1 proof chip row
	2.	Proof strip (logos + outcomes metrics)
	3.	Capabilities grid (3–5)
	4.	Method / process stepper
	5.	Case studies teaser (2–3)
	6.	Industries / use-cases (light)
	7.	Testimonials (optional)
	8.	CTA band + form

H2 — AI Micro-SaaS
	1.	Hero (value prop) + CTA: Start free + secondary: Request demo
	2.	Feature stack (core loop)
	3.	Integrations row
	4.	Trust bar (security/compliance + ratings)
	5.	Use-cases grid (teams)
	6.	Pricing preview (or full pricing)
	7.	Testimonials/quotes
	8.	CTA band

H3 — AI Trainers / Consultants
	1.	Hero (outcome + CTA: Explore programs / Book briefing)
	2.	Programs overview (tracks)
	3.	Curriculum modules (tabs/accordion)
	4.	Who it’s for (roles/industries)
	5.	Instructor credibility (bios)
	6.	Outcomes/proof (learner/corp)
	7.	Pricing optional (if applicable)
	8.	CTA band

3) Component kit (shared + per home)

Списък само на компоненти, но с variant notes:
	•	Header (simple dropdown only)
	•	Hero (3 variants)
	•	Cards system (service/feature/program/program)
	•	Proof strip (3 content modes)
	•	Stepper (H1)
	•	Integrations row (H2)
	•	Trust bar (H2)
	•	Pricing (H2 / optional H3)
	•	Curriculum tabs/accordion (H3)
	•	Case study cards (H1)
	•	CTA band + form

4) Copy rules (за “премиум” тон)
	•	One-line headlines, конкретни глаголи
	•	Забранени: vague claims (“best”, “revolutionary”) без proof slot
	•	Every claim must have a nearby proof slot (logo/metric/badge/testimonial)
