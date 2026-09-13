# Caleb Ponce

**Full-stack developer building reliable products with explainable decision logic.**

I build web applications where the difficult part is not just generating an answer—it is making that answer safe, testable, and understandable. My recent work combines React interfaces, backend APIs, deterministic planning systems, applied AI, and automated delivery.

## Quick review path

If you have a minute, start with the project closest to the role:

| For roles focused on… | Review… | What to look for |
| --- | --- | --- |
| Full-stack systems and operational reliability | [RunSignal](https://runsignal-caleb.mheaeduardo.chatgpt.site) | Explainable release triage built from live public CI evidence |
| Product engineering and safety-critical UX | [LayoverPlus](https://calebponce.github.io/Layover-Plus/) | A deterministic go/no-go travel decision with visible timing assumptions |
| Backend logic, optimization, and applied AI | [Home4U](https://calebponce.github.io/Home-4-U/) | Constraint-valid shopping strategies with transparent budget tradeoffs |

## Selected work

### [Home4U](https://github.com/calebponce/Home-4-U) · [Live case study](https://calebponce.github.io/Home-4-U/)

An explainable room-planning platform that converts design signals and hard budgets into constraint-valid purchasing strategies.

- Led team delivery and system architecture for the original React/FastAPI application.
- Added a deterministic optimizer that compares thousands of valid product combinations across three visible strategy objectives.
- Bounded the worst-case optimizer search to 196,605 strategy combinations and added reproducible benchmarks plus budget, uniqueness, and accounting invariants.
- Built a zero-sign-in public case study with responsive interaction, automated tests, CI, and GitHub Pages delivery.

### [LayoverPlus](https://github.com/calebponce/Layover-Plus) · [Live case study](https://calebponce.github.io/Layover-Plus/)

A risk-aware micro-itinerary planner that answers whether a traveler can safely leave an airport during a layover.

- Contributed AI and backend engineering to the original three-person SFSU application.
- Separates deterministic timing and feasibility rules from optional Gemini-assisted ranking and explanations.
- Uses conservative fallbacks when AI, place discovery, or routing providers are unavailable.
- Includes API contracts, browser-level interaction coverage, validation, rate limiting, deterministic safety-boundary tests, and automated CI.
- Added a zero-sign-in interactive case study that exposes the safety math, rejects one-minute timing overruns, and deploys a lightweight GitHub Pages build.

### [RunSignal](https://github.com/calebponce/RunSignal) · [Live demo](https://runsignal-caleb.mheaeduardo.chatgpt.site)

A solo CI reliability console that turns workflow evidence into explainable release decisions.

- Designed and built the product independently, from triage rules and edge API to interface, tests, and deployment.
- Loads real public GitHub Actions history and normalizes workflow, job, commit, queue, retry, and branch evidence.
- Classifies code regressions, flaky tests, infrastructure pressure, and dependency incidents without hiding the evidence.
- Produces conservative ALLOW, HOLD, or BLOCK recommendations and returns inconclusive when the evidence is weak.
- Runs as a public full-stack demo without sign-in, paid services, or private-repository credentials.

## Engineering approach

- Keep business-critical decisions deterministic and auditable.
- Use AI to enhance ranking and communication—not to override safety constraints.
- Expose tradeoffs in the product instead of hiding them behind a single score.
- Ship with tests, accessibility checks, diagnostics, and repeatable deployments.

## Core tools

`JavaScript` · `React` · `Node.js` · `Express` · `Python` · `FastAPI` · `SQLAlchemy` · `REST APIs` · `Playwright` · `GitHub Actions` · `Applied AI`

I am currently seeking software engineering opportunities where I can contribute across product, frontend, backend, and system design.
