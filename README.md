# Aerarium Res Publica

> *The Treasury of the Public Thing*

ORGANVM's institutional wing — the legal, financial, and governance infrastructure that transforms a 126-repo open-source system into a fundable institution.

## What This Is

This repository manages the transition from ORGANVM-as-software to ORGANVM-as-institution:

- **Entity Formation** — LLC, fiscal sponsorship, 501(c)(3) pathway
- **Grant Applications** — NLnet, Creative Capital, Sloan, NSF POSE, residencies
- **Donor Infrastructure** — Candid profile, GitHub Sponsors, Every.org, Benevity
- **IP Policy** — Open-core model mapping organs to licenses
- **Institutional Strategy** — Phased roadmap from fiscal sponsorship to Mozilla model

## Structure

```
aerarium--res-publica/
├── applications/           # Active grant/fellowship applications
│   ├── nlnet-ngi0-commons-2026/
│   ├── creative-capital-2027/
│   ├── aspiration-tech-fiscal-sponsor/
│   ├── sovereign-tech-fellowship-2026/
│   ├── zkm-rauschenberg-2026/
│   └── sloan-foundation-loi/
├── entity-formation/       # Legal entity setup
│   ├── llc/
│   ├── candid/
│   ├── github-sponsors/
│   └── ip-policy.md
├── strategy/               # Master strategy + structural research
├── research/               # Application-specific research
├── docs/                   # Governance docs, templates
└── seed.yaml
```

## Dual-Entity Model

```
FISCAL SPONSOR (Aspiration Tech)  ←  501(c)(3)
  │
  ├── ORGANVM Open Project
  │     ├── Organ I   (Theoria)    — Research
  │     ├── Organ II  (Poiesis)    — Art
  │     ├── Organ IV  (Taxis)      — Governance (open-source)
  │     ├── Organ VI  (Koinonia)   — Community
  │     └── META                   — Registry, schemas
  │
YOU
  │
  └── ORGANVM LLC
        ├── Organ III  (Ergon)     — Commercial SaaS
        ├── Organ V   (Logos)      — Publishing
        └── Organ VII (Kerygma)    — Distribution
```

## Cvrsvs Honorvm

The extracted governance engine — the NLnet application's central deliverable. Named after the Roman *cursus honorum* (sequential order of public offices). ORGANVM orthography: V for U.

- **Repo:** [meta-organvm/cvrsvs-honorvm](https://github.com/meta-organvm/cvrsvs-honorvm)
- **PyPI:** `cvrsvs-honorvm` (not yet published)
- **License:** Apache 2.0
- **Status:** INCUBATOR — extraction from [organvm-engine](https://github.com/meta-organvm/organvm-engine) in progress
- **R&D question:** Can formal governance be declaratively specified as a portable open standard?

## Active Deadlines

| Date | Opportunity | Amount | Status |
|------|-------------|--------|--------|
| **2026-04-01** | NLnet NGI0 Commons — Cvrsvs Honorvm | EUR 37,080 | **DRAFT COMPLETE** — human review + submit |
| **2026-04-02** | Creative Capital 2027 | $15K-50K | BLOCKED (need work sample video) |
| **2026-04-06** | Sovereign Tech Fellowship | Varies | RESEARCH |
| **2026-04-12** | ZKM Rauschenberg | Funded | RESEARCH |
| Rolling | Aspiration Tech fiscal sponsor | Unlocks all | READY |
| Rolling | Sloan Foundation LOI | $50K-$1M | READY |

## Omega Closure

The institutional wing advances 13 of 17 omega criteria. Current state: **4/17 MET**. Target: **17/17 by Q2 2027**. See `.claude/plans/2026-03-25-omega-closure-plan.md` for the full plan.

## Organ

**META-ORGANVM** — Constitutional layer. This is system-level governance, not personal career infrastructure.
