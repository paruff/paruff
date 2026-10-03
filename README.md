## Phil Ruff · @paruff

I build open-source platform engineering tools for small teams that work with
AI coding agents, and I build them in public. Each stack is small enough to
run on a laptop, does one job, and states what it doesn't do yet.

### The uFawkes suite

Every repo below is generated from **uFawkesAI** and develops inside its
devcontainer, `ghcr.io/paruff/fawkes-space`.

| Repo | What it is | Where it is |
|---|---|---|
| [🤖 uFawkesAI](https://github.com/paruff/uFawkesAI) | Template for AI-native development: one config for Claude Code, OpenCode, Codex and Gemini CLI; an `intent → spec → plan` chain checked in CI; agent evals that gate merges; and the shared devcontainer image | `v2.0.0` in release candidate |
| [📊 uFawkesObs](https://github.com/paruff/uFawkesObs) | Docker Compose observability stack: OpenTelemetry, Prometheus, Loki, Tempo, Grafana. Computes delivery (DORA) metrics from pipeline events | `v0.2.0`, heading to `v1.0.0` |
| [🔧 uFawkesPipe](https://github.com/paruff/uFawkesPipe) | Woodpecker CI pipeline contract with security scanning, for any language | `v1.7` beta, heading to `v2.0.0` |
| [🛠️ uFawkesDevX](https://github.com/paruff/uFawkesDevX) | Developer portal and golden-path templates | Pre-release, heading to `v0.1.0` |
| [🥋 uFawkesDojo](https://github.com/paruff/uFawkesDojo) | Belt-level platform engineering curriculum; each lab is built on a released stack | `0.1.0-alpha` |
| [🦅 fawkes](https://github.com/paruff/fawkes) | Kubernetes internal delivery platform (Tekton, Argo CD, Grafana) for teams that outgrow Compose | Pre-alpha, heading to Tracer Bullet Alpha |

[ufawkes.dev](https://ufawkes.dev) has a page for each stack, the
[compatibility matrix](https://ufawkes.dev/compatibility/) of which versions
were tested together, and a live [release status](https://ufawkes.dev/status/).

### How I work

Releases are gate-driven, not date-driven: a stack ships when its acceptance
criteria pass, and a claim that can't be verified gets removed instead of
rushed. AI agents implement; I decide and review.

**Based in Óbidos, Portugal 🇵🇹**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-phil--ruff-0077B5?style=flat-square&logo=linkedin)](https://linkedin.com/in/phil-ruff)
[![ufawkes.dev](https://img.shields.io/badge/ufawkes.dev-platform%20engineering-1e2327?style=flat-square)](https://ufawkes.dev)
