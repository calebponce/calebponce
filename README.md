# Caleb Ponce

**Software engineer building AI applications with explainable decision logic.**

I build web applications where the difficult part is not just generating an answer—it is making that answer safe, testable, and understandable. My recent work combines React interfaces, backend APIs, deterministic planning systems, applied AI, and automated delivery.

## Quick review path

If you have a minute, start with the project closest to the role:

| For roles focused on… | Review… | What to look for |
| --- | --- | --- |
| AI application engineering | [LayoverPlus](https://calebponce.github.io/Layover-Plus/) | Optional Gemini ranking behind deterministic feasibility, fallback, and mocked-provider tests |
| Applied AI and optimization | [Home4U](https://calebponce.github.io/Home-4-U/) | Constraint-valid shopping strategies with transparent budget tradeoffs |
| Full-stack reliability | [RunSignal](https://runsignal-caleb.mheaeduardo.chatgpt.site) | Explainable release triage built from public CI evidence |
| Startup product engineering | [Hardline engineering showcase](https://calebponce.github.io/hardline-engineering-showcase/) | A synthetic interactive case study for a private AR utility-record product |

## Selected work

### [Hardline](https://github.com/calebponce/hardline-engineering-showcase) · [Live case study](https://calebponce.github.io/hardline-engineering-showcase/) · [Product site](https://hardline-seven.vercel.app/)

A native iOS capture and web review platform for documenting utilities before walls close. I am a co-founder and full-stack engineer. The production repository is private; the linked public case study explains selected engineering decisions with synthetic data.

- Integrated an RGB-only reconstruction path into scan processing and strengthened authentication and request boundaries.
- Delivered durable room identity, controlled public review links, 2D utility-map review, and field-facing iOS scan-flow fixes.
- The [contribution record](https://github.com/calebponce/hardline-engineering-showcase/blob/main/CONTRIBUTIONS.md) explains attribution and what outside reviewers can verify.

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
- Loads real public GitHub Actions history and normalizes workflow, job, commit, queue, run-attempt count, and branch evidence; earlier retry outcomes remain unknown unless verified.
- Classifies code regressions, flaky tests, infrastructure pressure, and dependency incidents without hiding the evidence.
- Produces conservative ALLOW, HOLD, or BLOCK recommendations and returns inconclusive when the evidence is weak.
- Runs as a public full-stack demo without sign-in, paid services, or private-repository credentials.

## Engineering approach

- Keep business-critical decisions deterministic and auditable.
- Use AI to enhance ranking and communication—not to override safety constraints.
- Expose tradeoffs in the product instead of hiding them behind a single score.
- Ship with tests, accessibility checks, diagnostics, and repeatable deployments.

## Core tools

`TypeScript` · `JavaScript` · `React` · `Node.js` · `Express` · `Python` · `FastAPI` · `SQLAlchemy` · `REST APIs` · `Playwright` · `GitHub Actions` · `Applied AI`

I am currently seeking AI application engineering opportunities where I can contribute across product, frontend, backend, and system design.
