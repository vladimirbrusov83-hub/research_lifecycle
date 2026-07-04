# The Research Lifecycle

An interactive, single-file visual essay mapping the ten phases of scientific research — and showing who carries the load at each step: the **researcher** (human judgment), **agentic AI** (velocity & automation), and the **academic library** (trust, access, permanence).

**Live:** https://vladimirbrusov83-hub.github.io/research_lifecycle/

## What it covers

The full research pipeline, phase by phase:

1. Problem & Question
2. Literature Review
3. Hypothesis & Framework
4. Research Design & Methodology
5. Data Collection
6. Data Analysis
7. Interpretation & Writing
8. Peer Review & Submission
9. Publication & Dissemination
10. Post-Publication: Impact & Reuse

For every phase it lays out what the researcher owns, what AI reliably does today (and what's emerging), where the library leads, and the honest tension where the lanes overlap — is the output a *suggestion*, or a *record* that has to stand up in review?

## Interactive features

- **Load-shift curve** — an animated SVG plotting how researcher / AI / library effort rises and falls across all ten phases. Hover any point for detail; click to jump to that phase.
- **Isolate a line** — hover the entity chips in the hero to spotlight a single support system on the curve.
- **Expandable phase cards** — open each phase for key decisions, tools researchers actually use, what to watch for, and what to ask a librarian.
- **Library Lens** — a toggle that dims everything except the institutional layer.
- **Scroll progress**, reveal-on-scroll animations, and active-phase syncing between the map and the cards.
- Respects `prefers-reduced-motion`.

## Tech

A single, dependency-free `index.html` — vanilla HTML/CSS/JS, Google Fonts (Fraunces, Spectral, JetBrains Mono). No build step. Open the file locally or visit the live page.

## Design

Warm-paper aesthetic with a serif display face — built to read like a printed field guide rather than a dashboard.
