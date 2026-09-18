# PV + BESS Industrial Reference Electrical Design

> Portfolio reference work derived from public job postings (CONTEXT-BOUND / PLANNED). Source jobs are requirements inspiration only; no client execution, fabrication, bench test or production claim is made.

**Status:** INITIAL / EVIDENCE REQUIRED · **Workspace phase:** Phase 3 · **Source:** JOB-04 (+ JOB-05 documentation concepts)
**Handoff ID:** `CAN-ENERGY-PORTFOLIO-2026-09-15`

## Goal
Produce a reproducible reference electrical design for an industrial load supplied by PV, BESS, grid and optional backup generation, inspired by JOB-04 and documentation concepts from JOB-05.

## Current scope
Phase 3 project; detailed model/design directories are deferred until assumptions and calculation methodology are explicit. Canonical requirement prefix: `PVB-` (not yet defined).

## Required future artifacts
Assumptions, load profile, load analysis, PV/BESS sizing, generator strategy, operating modes, single-line diagram, equipment schedule, calculation methodology, simulation results, limitations, decision register and validation matrix.

Empty implementation-stage directories are intentionally not created until useful artifacts exist.

## Repository layout
```
pv-bess-system-design/
├─ README.md
└─ docs/00_shared/   # governance mirrored from workspace
```

## Governance
- Source jobs are requirements inspiration only; they are not evidence of client execution.
- VERIFIED / VALIDATED / TESTED / PASS / COMPLETE / PRODUCTION READY / MANUFACTURING READY require evidence paths — see [evidence_policy](docs/00_shared/evidence_policy.md).
- Hardware status is limited to DESIGNED, SIMULATED, FABRICATED, ASSEMBLED, BENCH_TESTED, FIELD_TESTED — see [terminology](docs/00_shared/terminology.md).
- Major architecture choices are recorded in decision registers; unknowns remain OPEN or BLOCKED — see [engineering_rules](docs/00_shared/engineering_rules.md).

## Workspace execution order

| Phase | Scope |
|---|---|
| 0 | Governance + job-source map + requirement templates |
| 1 | Project 01 and Project 02 baselines |
| 2 | Project 03 |
| 3 | Project 04 |
| 4 | Cross-project consistency |
| 5 | Releases only when evidence is traceable |

Related repositories: see [portfolio_map](docs/00_shared/portfolio_map.md).
