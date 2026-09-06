## What's inside

13 topics, organized into four phases plus an orientation topic — the same structure the reader's own landing page uses:

**Orientation**
1. Introduction to the Course

**Diagnose**
2. Composite Indices & AHP
3. PCA & Clustering

**Understand**
4. Digital Infrastructure (IoT, Big Data, Digital Twins, GIS)
5. E-Governance & Participatory Mechanisms
6. Financing Models: PPP & Grants

**Forecast**
7. Trends & Regression
8. Scenario Planning & Foresight (Delphi, System Dynamics)
9. Spatial Modeling & Urban Growth (GIS)

**Risk & Act**
10. Urban Resilience Assessment & Risk Management
11. Smart Reconstruction of Ukrainian Cities After the War
12. Project Development & Monitoring: KPIs
13. Case Studies & Student Project Defense

Each topic page includes worked examples with real numbers, original diagrams (no stock chart templates), a short "try it yourself" interactive exercise, and links to primary sources where a claim is directly traceable to one (Saaty, Giffinger, Pearson, Arnstein, RAND, the World Bank, etc.).

## How it's built

- **Single HTML file, zero JavaScript.** Navigation runs entirely on native anchor links (`#topic-3`, `#s3-1`, …) and CSS `position: sticky` — a deliberate choice after an early JS-routed version broke in a sandboxed preview that didn't execute scripts. Everything is visible in the page source and works the same with scripts disabled.
- **Interactivity** uses native `<details>/<summary>` for the reveal-the-answer exercises — no JS needed there either.
- **Diagrams** are hand-built inline SVG, each specific to what it's illustrating (a pairwise-comparison matrix, a network graph, a stock-and-flow loop) rather than a generic chart type.
- **Design system:** a cool off-white paper background, a serif body face, and a monospace face reserved for section numbers, navigation, and diagram labels — see the `:root` CSS variables at the top of the file to retheme.

## Navigating the reader

The landing page's topic map is a jump-to-anything index, not a forced reading order. Inside a topic, the sticky bar at the top (`← All 13 topics` / `↑ Contents`) and the section-map under each topic's title work the same way at the topic level — click any subsection to jump straight to it.

## Status

All 13 topics are complete. The formal syllabus document (competencies, ECTS hours, assessment breakdown) is a separate deliverable from this reader and isn't included here.
