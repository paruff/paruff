## Phil Ruff · @paruff

Building the open-source platform engineering stack for teams working with AI.

**The uFawkes family** — composable Docker stacks that implement the DORA AI Capabilities Model:

| Stack | What it does | Status |
|---|---|---|
| [🦅 Fawkes](https://github.com/paruff/fawkes) | Full Kubernetes IDP — Backstage + ArgoCD + 6 DORA metrics. The graduation target once a team outgrows the Compose tier. | Active |
| [📊 uFawkesObs](https://github.com/paruff/uFawkesObs) | Prometheus + Grafana + AI observability, now owns DORA metrics computation | Active |
| [🔧 uFawkesPipe](https://github.com/paruff/uFawkesPipe) | Polyglot CI/CD pipeline contract, now owns security scanning/policy | Active |
| [🛠️ uFawkesDevX](https://github.com/paruff/uFawkesDevX) | Developer control plane | In progress |
| [🥋 uFawkesDojo](https://github.com/paruff/uFawkesDojo) | Belt-level platform engineering curriculum for uFawkes and Fawkes | Active |

Not a stack — the template the whole family (including this list) is built from:

| | What it does |
|---|---|
| [🤖 uFawkesAI](https://github.com/paruff/uFawkesAI) | `AGENTS.md` template for all AI coding agents — every uFawkes/Fawkes repo is scaffolded from it |

**Retired (2026-08-18):** uFawkesRes (resources plane) and uFawkesSec (security) are no longer part of the active uFawkes suite — their responsibilities folded into Obs (DORA metrics) and Pipe (security scanning) respectively. See [uFawkesObs's retirement notes](https://github.com/paruff/uFawkesObs/blob/main/docs/notes/res-status.md) for the Res rationale.

make dev-up   # Fawkes full IDP running locally in ~20 minutes

docker compose up   # any uFawkes stack running in <60 seconds

**Based in Obidos, Portugal 🇵🇹 · Building in public · [ufawkes.dev](https://ufawkes.dev)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-phil--ruff-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/phil-ruff)
[![Fawkes](https://img.shields.io/badge/ufawkes.dev-platform%20engineering-1e2327?style=flat-square)](https://ufawkes.dev)

Building @paruff/fawkes — open-source DORA AI Capabilities platform · ufawkes.dev
