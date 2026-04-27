# FreightSimple · Marketing Operating Hub

The internal marketing dashboard for FreightSimple. A system of editorial HTML documents — a hub that orchestrates, four strategic docs that hold the thinking, and supporting deliverables that ship the work.

**Live at:** [danielapeream.github.io/freightsimple-marketing-ops-hub](https://danielapeream.github.io/freightsimple-marketing-ops-hub/)

---

## What this is

A single source of truth for marketing strategy, audience definition, execution plays, and shipped work. Built to replace scattered Word docs, Notion pages, and Google sheets with a coherent, navigable system.

The hub (`index.html`) is the dashboard. The four core documents — Audit, Customer, Strategy, Plays — hold the substantive content. They cross-link to each other so any reader can navigate the system contextually rather than alphabetically.

---

## The system at a glance

```
                    ┌─────────────────┐
                    │       Hub       │
                    │   (index.html)  │
                    └─────────────────┘
                            ↑
                            │ ← Back to hub (every doc returns here)
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
        ▼                   ▼                   ▼
   ┌─────────┐         ┌──────────┐        ┌──────────┐
   │  Audit  │ ←─────→ │ Strategy │ ←────→ │  Plays   │
   └─────────┘         └──────────┘        └──────────┘
        ↑                   ↕
        │                   │
        └─────→ ┌────────────┐
                │  Customer  │
                └────────────┘
```

Each doc stands on its own. Read together, they form a coherent argument: what we found, who we serve, what we do, how we execute.

---

## File index

### Core dashboard

| File | Purpose |
|---|---|
| `index.html` | The hub. 10 sections + resource library. Navigates to every other doc. |

### The four strategic documents

| File | Purpose |
|---|---|
| `audit.html` | **The Audit** · Consolidated diagnostic — funnel groups, competitive landscape, unique moats, channel-by-channel state, priority opportunities. The full diagnostic in one read. |
| `customer.html` | **The Customer** · ICP definition, three buyer personas (Alex / Sandra / Michael), geography, signals, and six insights from sales shadowing that reshaped the strategy. |
| `strategy.html` | **The Strategy** · Strategy tree (thesis v1 → v2), Three Moves, Three Pillars, Moves×Pillars matrix, tagline, voice, three claims (Save / Predict / Simplify), persona messaging, objection handling, proof points library. |
| `plays.html` | **The Plays** · Execution layer — 6-stage funnel with entry/exit/play per stage, the email engine, Retention Sequence v2.0 dollar-first proposal, and the 8 principles behind every email decision. |

### Supporting deliverables

| File | Purpose |
|---|---|
| `website-restructure-plan.html` | Strategic plan for the site restructure — IA, sitemap (240 → 88 pages), redirects, adaptive Solutions page, execution phases. Built for the meeting with Chris and Natasha. |
| `shipped-inventory.html` | Complete 17-deliverable inventory with status per item. The execution layer for the dashboard. |
| `visual-system.html` | The design system rationale — typography, color palette, component patterns, voice attributes. |

---

## How to use it

**Reading the system:**
Start at the hub. From there, follow either the curated narrative (the section flow) or jump directly to a strategic document via the Resource Library at /10. Each document includes a back-link to return to the hub.

**Sharing with someone new:**
Send them the live URL. The hub explains itself. For deeper context on any topic, they can open the relevant doc.

**Presenting strategy work:**
Open `strategy.html` directly. It's the most complete narrative artifact and stands alone as a deliverable.

---

## How to update

Each `.html` file is fully self-contained — HTML, CSS, and minimal JavaScript all live inline. There is no build step, no compilation, no dependencies. To update a document, edit its file and commit.

**When updating a strategic doc:**
1. Edit the relevant `.html` file directly
2. If you add a new section with an `id`, consider whether other docs should link to it
3. Commit with a descriptive message

**When adding a new doc:**
1. Use one of the existing strategic docs as a template (the visual system is consistent across all)
2. Place it in the repo root
3. Add an entry to the hub's Resource Library (`index.html`, search for `/10`)
4. If it warrants prominent placement, add a dedicated section in the hub
5. Add it to this README under "File index"

**When the cross-link map changes:**
- Update both ends — the originating doc and the destination
- Anchor links use the format `filename.html#section-id`
- All paths are relative; everything lives in the repo root

---

## Visual system

All documents share a consistent design language:

- **Typography:** Plus Jakarta Sans (display) · Inter (body) · JetBrains Mono (technical)
- **Palette:** `#1a1d23` dark · `#facc0b` gold · `#4C62EA` blue · `#1D9E75` success · `#BA7517` warning
- **Patterns:** Brand strip with back-link · doc-meta eyebrow · executive summary in dark with gold top-line · gold-on-gold-light section labels · cream blocks for open questions
- **Voice:** 80% Stripe (precise, useful, respectful of time) · 15% Linear (calm, restrained) · 5% Mailchimp (microcopy with personality)

Full rationale in `visual-system.html`.

---

## Tech notes

- **No build step.** Static HTML files. Every file is self-contained — open one in any browser and it just works.
- **No frameworks.** Vanilla HTML, CSS, JavaScript. Embedded styles per file.
- **GitHub Pages.** Deployed automatically on push to main.
- **Browser support.** Modern browsers (Chrome, Edge, Firefox, Safari). Responsive down to ~380px.

---

## Roadmap

**Live now (April 2026):**
The hub, four strategic docs, website restructure plan, shipped inventory, visual system rationale.

**In progress:**
Brand book, internal team handbook, dispatch sample, Q3 carrier-side documents.

**Future:**
The Q3 docs will live alongside the existing ones — a Carrier Audit, carrier personas, and carrier messaging — once Pillar 03 (the supply side) becomes the active workstream.

---

## Maintainer

**Daniela Perea** · Marketing Lead, FreightSimple

Last updated · April 2026
