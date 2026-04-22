# FreightSimple — Marketing Dashboard (2-Week Recap)

Interactive dashboard summarizing 2 weeks of marketing work — strategy, brand, website, video, hiring.
Single HTML file, no build step, deploys straight to GitHub Pages.

## Purpose

Leadership-facing recap prepared for Chris Stott. Hybrid format:
- **Hero with big impact numbers** — 20+ deliverables, 30+ KPIs, 6 funnel stages, 3 communication pillars
- **/01 Insights we discovered** — six data-driven findings from the audit, each reshaped a decision
- **/02 The new funnel + strategic plays** — 6-stage model (Aware → Retained) with priority action per stage + 6 strategic plays mapped against it
- **/03 Three communication pillars** — audience-based: Internal, Users &amp; Clients, Carriers
- **/04 Everything shipped** — 20+ deliverables grouped by pillar
- **/05 Waiting on decision** — 5 leadership decisions that unblock what's next

Solo planning and execution throughout. Structure walks from data → strategy → execution → what needs sign-off.

## What's here

- `index.html` — the full dashboard (single file, no dependencies)
- `logo-icon.png` — official FreightSimple logo icon
- `README.md` — this file

## Publishing to GitHub Pages

Upload all three files to the root of a new repo. Then:

1. Settings → Pages → Source: *Deploy from a branch* → Branch: `main` → Folder: `/ (root)` → Save
2. Wait ~1 minute, site goes live at `https://danielapeream.github.io/<repo-name>/`

## Design

Follows Brand Book v1.0 strictly:
- **Colors:** FreightBlue `#4C62EA`, FreightGold `#facc0b`, FreightDark `#1a1d23`
- **Typography:** Plus Jakarta Sans (display) · Inter (body) · JetBrains Mono (labels/numbers)
- **Aesthetic:** "Operations report, not pitch deck" — giant numbers, monospace labels, clean card system, restrained gold

Interactions:
- Count-up animation on hero metrics
- Scroll-triggered reveals on cards
- Accordion expand/collapse with rotating chevron
- Top scroll-progress bar
- Sticky top nav with jump-links

## Content sources

All content pulled from:
- Q2 Baseline Report (April 2026)
- Core Messaging Framework
- Brand Book v1.0
- Marketing Hire Feedback doc
- Homepage Redesign Proposal + Prototype v2.1
- Video Explainer Brief + Final Script (Moon Shipment)

## Built by

Daniela Perea · Marketing Lead · April 2026
