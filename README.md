# 🛰 Talent Intelligence Playbook

Stop guessing whether a hire is hard. A field library that walks a recruiter from "we have an open req" to a defensible, data-backed talent verdict - built for semiconductor and AI engineering markets where the title on the JD rarely matches the talent on the ground.

![License](https://img.shields.io/badge/license-MIT-0F6E56)
![GitHub Pages](https://img.shields.io/badge/hosted-GitHub%20Pages-1B212C?logo=github)
![Made for](https://img.shields.io/badge/built%20for-talent%20intelligence-BA7517)

- 🗺 **Map a market before you commit to it** - geo concentration, competitor talent bases, and new-market entry, with copyable Boolean strings and AI prompts tuned for RF, analog IC, CUDA, and tape-out talent
- 📊 **Hand leadership a decision, not a dashboard** - build-vs-buy location strategy and a live pipeline-health diagnostic that reads coverage and flow instead of raw candidate counts
- 🔗 **One connected system, not 14 loose files** - every guide cross-links to the steps and modules it depends on, so you move from learning to doing to selling without losing your place

---

## Three ways in

The library serves the same reader in three different modes. The front door (`index.html`) routes you to the right one.

- **I'm learning** - the flagship talent supply snapshot guide and reference material, for building the mental model
- **I'm doing** - the operational guides and step modules, for executing a real task this week
- **I'm selling** - the Tier 3 leadership briefs, for handing an exec a decision they can act on

---

## What's inside

### The field library — "I'm doing"

- 📸 **Pull a talent supply snapshot** - the flagship 7-step method for sizing how hard a specific hire really is
- 🎯 **Run a competitor talent analysis** - three competitor lists (direct ≠ talent ≠ aspirational), org mapping, and a copyable battlecard template
- 🌏 **Map a talent pool for a new market** - the Draup five-lens framework applied to a real entry decision
- 🧩 **Build a skills-based talent map** - find the people when no one has the exact title
- 🔄 **Set up an always-on intelligence cadence** - standing watches, living documents, RACI, and event triggers that turn TI from heroic projects into a capability
- 📋 **Brief a hiring manager with market data** - the tactical playbook for the conversation that resets expectations

### Leadership briefs — "I'm selling"

- 🏗 **Build vs buy location strategy** - names all four pathways, not the binary leadership walked in with, with an interactive pathway recommender
- 🩺 **Pipeline health check** - a live dashboard that toggles between an at-risk and a healthy quarter so you can see what coverage, source diversity, and flow look like in good and bad shape

### Step modules — Guide 01 deep dives

- 📍 **Map geo concentration** - standalone light module on pulling and reading hub distribution

---

## The guide library

| Guide | Solves | File |
|---|---|---|
| Index / front door | Pick the right guide for the task | `index.html` |
| 01 — Talent supply snapshot | "How hard is this hire?" | `talent-supply-snapshot-guide.html` |
| 03 — Competitor talent analysis | "Where do they hire from and lose to?" | `library-guide-03-competitor-analysis.html` |
| 04 — New market mapping | "Should we open in this market?" | `library-guide-04-new-market-mapping.html` |
| 05 — Skills-based talent map | "No one has the title - who has the skills?" | `library-guide-05-skills-based-map.html` |
| 06 — Always-on cadence | "How do we run TI as a program?" | `library-guide-06-always-on-cadence.html` |
| 2.1 — Hiring manager brief | "How do I reset their expectations?" | `tactical-brief-hiring-manager.html` |
| 3.1 — Build vs buy location | "Where should this team live?" | `library-guide-31-build-vs-buy.html` |
| 3.2 — Pipeline health check | "Is this pipeline actually healthy?" | `library-guide-32-pipeline-health-check.html` |
| Step 3 — Geo concentration | "Where is this talent clustered?" | `light-map-geo-concentration.html` |

---

## Live demo

https://ohsusannamarie.github.io/talent-intelligence-playbook
<!--
---

## Screenshots

| | |
|---|---|
| ![Library front door — mode selector](screenshots/index-front-door.png) | ![Flagship guide with interactive tools](screenshots/flagship-guide.png) |
| ![Pipeline health dashboard](screenshots/pipeline-dashboard.png) | ![Competitor battlecard and xref system](screenshots/competitor-battlecard.png) |
-->
---

## Grounded in

The methods lean on named, current sources rather than generic best practice:

- **Toby Culshaw — _Talent Intelligence_** (Kogan Page, 2022) - the primary TI reference
- **Draup** - five-lens location strategy and the new-geography-of-work portfolio thesis
- **Lightcast, TalentNeuron, LinkedIn Talent Insights** - supply, demand, and skills data
- **Levels.fyi, Layoffs.fyi, H1B Data, WARN** - comp and movement signals

---

## Tech stack

| Layer | Tech |
|---|---|
| Frontend | Self-contained HTML, one file per guide |
| Styling | Vanilla CSS - "intelligence dossier" design tokens (Fraunces / Inter / IBM Plex Mono; paper / ink / teal / amber / rust) |
| Interactivity | Vanilla JS - dashboards, recommenders, copy-to-clipboard prompt and Boolean cards |
| Fonts | Google Fonts |
| Hosting | GitHub Pages (flat folder, relative links) |

No build step, no framework, no backend. Open any file in a browser and it runs.

---

## Repo structure

```
/
  index.html                                  ← front door (renamed from ti-playbook-index.html)
  talent-supply-snapshot-guide.html
  library-guide-03-competitor-analysis.html
  library-guide-04-new-market-mapping.html
  library-guide-05-skills-based-map.html
  library-guide-06-always-on-cadence.html
  tactical-brief-hiring-manager.html
  library-guide-31-build-vs-buy.html
  library-guide-32-pipeline-health-check.html
  light-map-geo-concentration.html
  screenshots/
  .nojekyll                                   ← serve files as-is, skip Jekyll
  LICENSE
  README.md
```

---

## Setup

```bash
git clone https://github.com/ohsusannamarie/talent-intelligence-playbook.git
cd talent-intelligence-playbook
open index.html
```

Every guide is a standalone file. Cross-references between guides use relative links, so the whole system works locally and on Pages with no configuration.

---

## License

[MIT](LICENSE) — use freely, attribution appreciated.

---

For every sourcer who has been handed a req and a number that doesn't match reality, and had to go find the truth themselves.
