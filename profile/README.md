<div align="center">

# CEO Online

**Agentic delivery systems with human-controlled release gates.**

We build operational control planes for AI-assisted engineering work: clear task contracts, runtime selection, claim safety, output gates, and review-first delivery.

![Focus](https://img.shields.io/badge/focus-agentic%20delivery%20control%20planes-0f766e?style=flat-square)
![Posture](https://img.shields.io/badge/posture-human%20approved%20automation-1f2937?style=flat-square)
![Safety](https://img.shields.io/badge/safety-no%20auto%20merge%20by%20default-b91c1c?style=flat-square)

</div>

## What We Build

CEO Online develops engineering workflow infrastructure for controlled agentic delivery.

| Area | What It Means |
|---|---|
| Agentic delivery | AI runtimes can work from structured tasks, not loose prompts. |
| Control plane | Linear, GitHub, local verification, and operator approval stay connected. |
| Safety gates | Secrets, closing keywords, direct `main` writes, and unsafe status transitions are blocked by policy. |
| Evidence-first operations | Every readiness step leaves a reviewable record before live execution expands. |

## Delivery Model

```text
Linear task
  -> contract and runtime selection
  -> claim and local verification
  -> branch / pull request handoff
  -> human review
  -> validation before Done
```

The default posture is conservative: agents may prepare work, but production-facing transitions require explicit approval and verifiable evidence.

## Current Focus

The active workstream is the **Agentic Delivery Control Plane**: a bridge between structured Linear issues, approved coding runtimes, local verification, and GitHub pull request delivery.

Core principles:

- One task, one selected runtime, one claim.
- No direct `main` changes from automation.
- No auto-close, no auto-merge, and no automatic `Done`.
- Secrets are consumed through approved wrappers only.
- Human validation remains the release boundary.

## Operating Standard

We optimize for systems that are useful under real operational constraints:

- readable contracts instead of hidden assumptions;
- small reversible changes instead of broad automation leaps;
- explicit evidence instead of trust-by-default reports;
- clear ownership boundaries between agents, operators, and release gates.

