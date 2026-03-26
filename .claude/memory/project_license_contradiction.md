---
name: License contradiction — META repos MIT vs IP policy Apache 2.0
description: All META repos declare MIT in pyproject.toml but IP policy says governance tools should be Apache 2.0. IRF-INST-017 tracks resolution.
type: project
---

All META-ORGANVM Python repos currently declare MIT license:
- organvm-engine: MIT (pyproject.toml + LICENSE)
- schema-definitions: MIT
- alchemia-ingestvm: MIT
- system-dashboard: MIT
- organvm-ontologia: MIT

The IP policy at `aerarium--res-publica/entity-formation/ip-policy.md` says ORGAN-IV and META governance tools should be Apache 2.0.

The new `cvrsvs-honorvm` extracted package will be Apache 2.0 (compatible with MIT provenance). The NLnet application explicitly notes this.

**Why:** MIT→Apache 2.0 relicensing is legally compatible (MIT is permissive), but needs a conscious decision: relicense all existing repos, or only new extractions.

**How to apply:** IRF-INST-017 tracks this. Any session touching licensing must check this memory.
