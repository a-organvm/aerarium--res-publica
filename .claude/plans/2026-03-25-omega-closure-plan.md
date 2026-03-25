# Omega Closure Plan — There and Back Again Through the Treasury

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Close the gap from 4/17 omega criteria MET to 17/17 — mapping every aerarium--res-publica action to the omega criterion it advances, with milestones and hard gates.

**Architecture:** The institutional wing (aerarium) is not a separate workstream — it IS the omega engine. Entity formation, grant applications, community infrastructure, and the Cvrsvs Honorvm extraction collectively advance 13 of 17 omega criteria. This plan maps macro (what omega looks like) → micro (every action, every criterion, every week) → macro (the system that emerges).

**Source:** `organvm-corpvs-testamentvm/docs/strategy/there+back-again.md` — the canonical omega roadmap. This plan extends it with the institutional dimension discovered in S37-S38.

---

## PART I: MACRO — THE CURRENT STATE

### Omega Scorecard (as of S38, 2026-03-25)

| # | Criterion | Status | Evidence | Institutional Lever |
|---|-----------|--------|----------|-------------------|
| 1 | 30-day soak test passes | IN PROGRESS | Soak test running since 2026-02-16 | — (system health, not institutional) |
| 2 | Stranger test ≥80% | NOT MET | Protocol ready, no participant | Cvrsvs Honorvm docs ARE a stranger test |
| 3 | Engagement baseline (30 days) | IN PROGRESS | Data collecting | — |
| 4 | Runbooks validated by 2nd operator | NOT MET | Written, not validated | Advisory board member could validate |
| 5 | ≥1 application submitted | **MET** | 60+ job apps; NLnet draft complete (submit by Apr 1) | NLnet = institutional application (different class than job apps) |
| 6 | AI-conductor essay published | **MET** | public-process essay #9 | — |
| 7 | ≥3 external feedback | IN PROGRESS | 2/3 (rejections + Carbone inbound) | NLnet reviewer feedback counts; Creative Capital feedback counts |
| 8 | ≥1 ORGAN-III product live | IN PROGRESS | Content engine skeleton, scrapper Phase 1 | — (commercial, not institutional) |
| 9 | revenue_status: live | IN PROGRESS | Carbone engagement scoped, not invoiced | LLC formation → invoice capability → revenue |
| 10 | MRR ≥ operating costs | NOT MET | $0 MRR | LLC + Sponsors → revenue channels |
| 11 | ≥2 events with external participants | NOT MET | Infrastructure only | FOSDEM presentation (NLnet T11) = 1 event |
| 12 | ≥3 external contributions | NOT MET | 5 good-first-issues exist | Cvrsvs Honorvm open-source = contribution surface |
| 13 | ≥1 organic inbound link | **MET** | Carbone found system via GitHub | — |
| 14 | ≥1 recognition event | IN PROGRESS | Carbone = potential adoption; NLnet = potential grant | NLnet award = recognition; ORCID + arXiv = academic recognition |
| 15 | Portfolio updated with validation | NOT MET | Portfolio live, no validation data | ORCID, arXiv, grant awards → validation evidence |
| 16 | Bus factor >1 | NOT MET | Runbooks written, not tested | Advisory board → bus factor |
| 17 | System operates 30+ days | IN PROGRESS | Soak test running | — |

**Score: 4/17 MET (#5, #6, #8, #13), 6/17 IN PROGRESS, 7/17 NOT MET**

### What the Institutional Wing Changes

The original there+back-again.md identified the core gap: "Everything that requires *other people* is at zero." The institutional wing — entity formation, grant applications, Cvrsvs Honorvm extraction — is the mechanism for crossing that gap. Without legal entity, no funding. Without funding, no community infrastructure. Without community, no omega.

**The aerarium thesis:** The system cannot reach omega as software alone. It must become an institution. Not because institutions are better than software, but because the omega criteria that remain unmet (#2, #4, #7, #9, #10, #11, #12, #14, #15, #16) all require *other people* — reviewers, contributors, operators, audiences, funders. An institution is the structure that lets other people participate.

---

## PART II: MICRO — THE PATH THROUGH THE TREASURY

### Phase 0: The Next 7 Days (March 25 — April 2)

**Gate:** NLnet submitted. Creative Capital assessed. ORCID registered. These are zero-excuse, calendar-gated actions.

- [ ] **Step 0.1: Register ORCID** (5 minutes)
  - Go to https://orcid.org/register
  - Complete registration
  - Link to Google Scholar if profile exists
  - **Advances:** #15 (portfolio validation), prerequisite for all academic funders
  - **IRF:** IRF-INST-016

- [ ] **Step 0.2: Human review of NLnet draft** (2-3 hours)
  - Read `applications/nlnet-ngi0-commons-2026/draft.md` aloud
  - Verify every technical claim against the codebase
  - Check: abstract (200-500 words), background (100-300 words), budget math
  - Decide final proposal name
  - **IRF:** IRF-INST-015

- [ ] **Step 0.3: Submit NLnet NGI0 Commons Fund** (30 minutes)
  - Web form at https://nlnet.nl/propose/
  - Select "NGI Zero Commons Fund"
  - Copy sections from draft.md into form fields
  - **Deadline: April 1, 2026 12:00 CEST**
  - **Advances:** #5 (MET, strengthened), #14 (recognition event pending)
  - **IRF:** IRF-INST-001

- [ ] **Step 0.4: Assess Creative Capital feasibility** (1 hour)
  - Check: do you have a completed work sample (video of artwork)?
  - If YES: begin draft at `applications/creative-capital-2027/`
  - If NO: defer — the video is blocking (roadmap task II-1)
  - **Deadline: April 2, 2026 3:00 PM ET**
  - **IRF:** IRF-INST-002

### Phase 1: Entity Formation (April 1-15)

**Gate:** LLC exists, bank account open, fiscal sponsor application sent. The dual-entity model is operational.

- [ ] **Step 1.1: Form ORGANVM LLC** (1-5 days, $50-500)
  - File articles of organization in home state (online, same-day in many states)
  - Sign operating agreement with mission statement
  - Get EIN at irs.gov (free, instant online)
  - Open bank account (Mercury or Relay, no minimum)
  - **Advances:** #9 (revenue infrastructure), #10 (invoicing capability)
  - **IRF:** IRF-INST-004

- [ ] **Step 1.2: Email Aspiration Tech** (30 minutes)
  - Send to fiscalservices@aspirationtech.org
  - Include: project description, budget, financial goals
  - Request Model C (project retains IP, LLC acceptable)
  - Pay $150 application fee
  - **Advances:** #14 (institutional partnership), #16 (bus factor via sponsor governance)
  - **IRF:** IRF-INST-003

- [ ] **Step 1.3: Set up GitHub Sponsors** (1 hour)
  - Enable on personal account (0% fee)
  - Configure tiers ($5/$10/$25/$50/$100/month)
  - Add FUNDING.yml to organvm-engine, cvrsvs-honorvm, schema-definitions
  - **Advances:** #9 (revenue channel live), #10 (recurring revenue possible)
  - **IRF:** IRF-INST-006

- [ ] **Step 1.4: Resolve license harmonization** (1 hour)
  - Decide: MIT→Apache 2.0 for all META repos, or Apache 2.0 for new only
  - If relicensing: update pyproject.toml + LICENSE in 5 repos, commit, push
  - **IRF:** IRF-INST-017

### Phase 2: Cvrsvs Honorvm Extraction (April 15 — June 15)

**Gate:** Standalone package on PyPI, external docs live, example project functional. This is the NLnet-funded work (whether or not the grant is awarded — the work advances omega regardless).

- [ ] **Step 2.1: State machine extraction** (40 hours)
  - Replace `ORGAN_LEVELS` hardcoded dict with configurable tier system
  - Replace `organvm_engine.paths` imports with config injection
  - Extract `check_transition()` and `execute_transition()` into standalone module
  - Make event emission pluggable (not dependent on EventSpine)
  - Write independent test suite
  - **Files:** Create `cvrsvs-honorvm/src/cvrsvs_honorvm/state_machine.py`
  - **Advances:** #12 (contribution surface), #14 (NLnet deliverable)
  - **IRF:** IRF-INST-018

- [ ] **Step 2.2: Dependency validator extraction** (40 hours)
  - Replace `all_repos()` import with abstract registry interface
  - Make organizational hierarchy configurable (not hardcoded directory names)
  - Extract `validate_dependencies()` and `build_multiplex_graph()` into standalone module
  - Write independent test suite
  - **Files:** Create `cvrsvs-honorvm/src/cvrsvs_honorvm/dependency_graph.py`

- [ ] **Step 2.3: Seed contract system extraction** (40 hours)
  - Replace workspace layout imports with pluggable discovery backends
  - Extract reader, graph builder, and validator
  - Write independent test suite
  - **Files:** Create `cvrsvs-honorvm/src/cvrsvs_honorvm/seed/`

- [ ] **Step 2.4: Documentation and PyPI publishing** (48 hours)
  - README with quickstart
  - API reference (auto-generated)
  - Tutorial: "Add governance to your multi-repo project in 15 minutes"
  - WCAG 2.1 AA compliant docs site
  - Publish to PyPI: `pip install cvrsvs-honorvm`
  - **Advances:** #2 (docs = stranger test surface), #12 (contribution surface)

- [ ] **Step 2.5: Example project** (64 hours)
  - 3-repo ecosystem (NOT ORGANVM)
  - Demonstrates: seed contracts, promotion transitions, dependency validation
  - Proves engine works outside origin context
  - **Advances:** #2 (stranger navigability), #7 (early adopter feedback)

- [ ] **Step 2.6: Interoperability** (56 hours)
  - Publish seed.yaml as open specification (CC-BY-4.0)
  - Import/export adapters for publiccode.yml and Backstage catalog-info.yaml
  - **Advances:** #14 (open standard = recognition), #12 (interop = contribution surface)

### Phase 3: Community Infrastructure (June — September)

**Gate:** External contributors exist, first event held, feedback collected.

- [ ] **Step 3.1: Open repos for contribution** (4 hours)
  - CONTRIBUTING.md on cvrsvs-honorvm, organvm-engine, schema-definitions
  - Code of conduct
  - 5+ "good first issue" labels with clear descriptions
  - Issue templates
  - **Advances:** #12 (contribution surface)

- [ ] **Step 3.2: Publish tutorial** (8 hours)
  - "How to Govern Your Multi-Repo Project with Cvrsvs Honorvm"
  - Publish on portfolio site (ORGAN-V)
  - **Advances:** #2 (stranger navigability), #6 (essay published — already MET but strengthened)

- [ ] **Step 3.3: Present at European event** (travel + 8 hours prep)
  - FOSDEM Infrastructure devroom or NLnet/NGI community meeting
  - Present Cvrsvs Honorvm and the governance engine
  - **Advances:** #11 (1 event with external participants), #14 (recognition event)

- [ ] **Step 3.4: Host first community event** (4 hours)
  - Online reading group, workshop, or salon
  - 3+ external participants
  - Topic: governance at scale for open-source ecosystems
  - **Advances:** #11 (2 events with external participants — MET with 3.3)

- [ ] **Step 3.5: Collect external feedback** (ongoing)
  - 3+ written feedback pieces from outside the system
  - On governance engine, research, or art
  - Sources: NLnet reviewers, FOSDEM attendees, tutorial readers, GitHub users
  - **Advances:** #7 (≥3 external feedback — MET)

### Phase 4: Academic Credibility (July — December)

**Gate:** ORCID active, first paper on arXiv, researcher profile exists.

- [ ] **Step 4.1: Submit first paper to arXiv** (40 hours writing)
  - "Promotion State Machines for Multi-Repository Governance" or equivalent
  - Based on INQ-2026-008 (The Cvrsvs Honorvm Inquiry)
  - **Advances:** #14 (recognition event), #15 (portfolio validation)

- [ ] **Step 4.2: Create researcher profiles** (2 hours)
  - Google Scholar profile
  - ResearchGate or Semantic Scholar
  - Link ORCID
  - **Advances:** #15 (portfolio updated with validation)

- [ ] **Step 4.3: Contact university faculty** (ongoing)
  - 3-5 faculty in DH, CS, media arts
  - Offer ORGANVM as research platform
  - Seek research affiliate status
  - **Advances:** #16 (bus factor — academic collaborators), prerequisite for NSF POSE

### Phase 5: Revenue and Sustainability (April — October)

**Gate:** LLC invoicing active, GitHub Sponsors live, ≥1 paying engagement.

- [ ] **Step 5.1: Invoice Carbone engagement** (if scoped work proceeds)
  - Issue invoice via LLC
  - Record revenue in registry
  - **Advances:** #9 (revenue_status: live), #10 (MRR toward operating costs)

- [ ] **Step 5.2: Ship first ORGAN-III product** (separate plan)
  - life-my--midst--in or content-engine--asset-amplifier
  - Deployed with payment integration
  - **Advances:** #8 (already IN PROGRESS), #9, #10

- [ ] **Step 5.3: Apply to additional funders** (rolling)
  - Sovereign Tech Fellowship (April 6)
  - ZKM Rauschenberg (April 12)
  - Sloan Foundation LOI (rolling)
  - NSF POSE Phase I (September 2026)
  - **Advances:** #14 (each application = potential recognition event)

### Phase 6: Operational Maturity (Ongoing)

**Gate:** Soak test passes, runbooks validated, bus factor >1.

- [ ] **Step 6.1: Complete soak test** (calendar time)
  - 30 consecutive days, ≤3 critical incidents
  - Generate soak test report
  - **Advances:** #1 (soak test passes), #17 (system operates 30+ days)

- [ ] **Step 6.2: Validate runbooks** (4 hours)
  - Advisory board member or trusted external person
  - Complete 3/6 key workflows using only runbook
  - **Advances:** #4 (runbooks validated), #16 (bus factor >1)

- [ ] **Step 6.3: Execute stranger test** (4 hours)
  - 1 external participant, zero context
  - 5-task protocol, scoring rubric
  - Target: ≥80%
  - **Advances:** #2 (stranger test passes)

- [ ] **Step 6.4: Establish engagement baseline** (30 days data)
  - Across 8 flagship repos
  - Documented in engagement report
  - **Advances:** #3 (engagement baseline established)

---

## PART III: MACRO — THE SYSTEM THAT EMERGES

### The Omega Closure Map

When all 17 criteria are met, the system exhibits the eight characteristics simultaneously:

| Characteristic | Criteria Fulfilled | Institutional Contribution |
|---------------|-------------------|---------------------------|
| Self-Healing Infrastructure | #1, #17 | Soak test proves automated governance works |
| Revenue Diversification | #9, #10 | LLC + Sponsors + grants = 3 revenue channels |
| Intellectual Contribution | #6, #14 | arXiv paper, Cvrsvs Honorvm specification |
| Community Activation | #11, #12 | FOSDEM + salon + open-source contributions |
| External Validation | #5, #7, #14, #15 | NLnet/CC applications, reviewer feedback, ORCID |
| Methodological Authority | #6 | AI-conductor essay (MET) + governance engine as method |
| Distribution Network | #13 | Organic inbound (MET) + tutorial + specification |
| Operational Maturity | #2, #3, #4, #16 | Stranger test, baselines, validated runbooks, advisory board |

### The Milestone Ladder — Gate-Based, Not Calendar-Based

Work is measured in energy expenditure (agent sessions, human gates), not time. Only external deadlines are calendar-bound. Each gate opens when its conditions are true, not when a month arrives.

| Gate | Conditions (what must be true) | Energy | Omega Impact | External Deadline |
|------|-------------------------------|--------|-------------|-------------------|
| **G0: SUBMITTED** | NLnet form submitted. ORCID registered. | 1 human session | #5 strengthened | **April 1, 2026 (HARD)** |
| **G1: DUAL-ENTITY** | LLC formed + EIN + bank. Aspiration Tech email sent. Sponsors live. | 1 human session + 2 agent sessions | #9, #10 initiated | — |
| **G2: EXTRACTED** | cvrsvs-honorvm state machine, dep validator, seed parser — all pass independent test suite. No ORGANVM imports. | 3-5 agent sessions (parallel: 1 per primitive) | #12 surface | — |
| **G3: PUBLISHED** | `pip install cvrsvs-honorvm` works. Docs site live. WCAG AA. | 2 agent sessions | #2, #12, #14 | — |
| **G4: PROVEN** | Example 3-repo ecosystem passes all governance checks. Engine works outside ORGANVM. | 2 agent sessions | #7, #11 | — |
| **G5: SPECIFIED** | seed.yaml open specification published. publiccode.yml + Backstage adapters. | 2 agent sessions | #14 | — |
| **G6: CITED** | arXiv paper submitted. Researcher profiles created. | 1 agent session + 1 human gate (review) | #14, #15 | — |
| **G7: COMMUNITY** | 3+ external feedback. 3+ contributions. 2+ events held. | Ongoing — human-gated (requires other people) | #7, #11, #12 MET | — |
| **G8: OPERATIONAL** | Soak test 30-day clean. Stranger test ≥80%. Runbooks validated. | Calendar-bound (30 days minimum) + 1 human gate (find participant) | #1, #2, #3, #4, #16, #17 MET | — |
| **G9: REVENUE** | revenue_status: live. MRR ≥ operating costs. | Human-gated (invoice, ship product) | #9, #10 MET | — |
| **G10: RECOGNIZED** | ≥1 grant awarded OR talk delivered OR adoption confirmed. Portfolio updated. | External-gated (reviewer decision) | #14, #15 MET | Grant cycles (6mo) |
| **OMEGA** | G0-G10 all passed. 17/17. | — | **The system simply is.** | — |

**Parallelism:** G0 is sequential (deadline). G1 and G2 are parallel. G3 depends on G2. G4 depends on G3. G5 is parallel with G4. G6 is parallel with G4/G5. G7 and G8 are ongoing. G9 depends on G1. G10 is externally gated.

**Critical path:** G0 → G2 → G3 → G4 (extraction is the bottleneck). Everything else is parallel or externally gated. With agent superpowers, the extraction (G2) can run 3 parallel agents — one per primitive. The bottleneck is human review gates, not agent energy.

### The Return

When the seventeenth criterion is met, the scaffolding comes down. The builder stops building and starts living in the building. The theory gets written. The art gets made. The community convenes. The products ship. And the infrastructure — the governance engine, the registry, the promotion state machine, the seed contracts — hums in the background, unnoticed. That is what omega means: the system succeeds when it becomes invisible.

The *cursus honorum* was the path Roman citizens walked to reach the highest offices. Each step had requirements. No step could be skipped. The path was public, formal, and constitutional. The same is true here. LOCAL → CANDIDATE → PUBLIC_PROCESS → GRADUATED → ARCHIVED. The system governs itself through the same mechanism it offers to others. Omega is when the mechanism needs no operator — when the *cursus* runs itself.

---

## APPENDIX: IRF Cross-Reference

| IRF Item | Plan Step | Omega Criteria |
|----------|-----------|---------------|
| IRF-INST-001 | 0.3 | #5, #14 |
| IRF-INST-002 | 0.4 | #5, #14 |
| IRF-INST-003 | 1.2 | #14, #16 |
| IRF-INST-004 | 1.1 | #9, #10 |
| IRF-INST-005 | 1.4 | — (prerequisite) |
| IRF-INST-006 | 1.3 | #9, #10 |
| IRF-INST-015 | 0.2 | #5 |
| IRF-INST-016 | 0.1 | #15 |
| IRF-INST-017 | 1.4 | — (consistency) |
| IRF-INST-018 | 2.1-2.6 | #2, #7, #12, #14 |
| INQ-2026-008 | 4.1 | #14, #15 |
