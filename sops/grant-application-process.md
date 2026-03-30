---
id: SOP-INST-001
title: "Grant Application Process — The Forced Revision Protocol"
scope: system
organ: META
tier: T3
status: active
---

# Grant Application Process

How any one thing is done = how every thing is done. The grant application process follows the same forced-revision methodology as every other production in the system: raw material → structure → purification → form. We don't pantomime — we don't fill in forms to check boxes. We build applications that are better than what we could have written in a single pass, because each revision takes the vision apart and puts it back together more purely.

**The drafting-vs-publishing distinction:** A word processor is a publishing tool that gets used as a drafting tool. A web form is a submission tool that gets used as a writing tool. Neither is where the work happens. The work happens in the revision cycle — in the forced transition between media that compels re-examination. Write the raw material in one medium. Revise into structure in another. Only pour into the final form when the vision has been purified through at least three revisions.

---

## Phase 1: RESEARCH (Parallel Agent Dispatch)

Before writing a single word of application text, research everything about the funder. Dispatch agents in parallel:

### Agent 1: Form Field Inventory
- Read the handbook/guidelines (PDF or web)
- Document EVERY field: name, type (text/dropdown/upload/checkbox), character/word limit, format constraints
- Note: is it plain text or rich text? File size limits? Naming conventions?
- Document fields the handbook doesn't mention but the form includes (demographic, surveys, eligibility confirmations)
- Output: `submission-checklist.md` with complete field inventory

### Agent 2: Past Winners Analysis
- Research 5-10 recent winners in your discipline/sub-discipline
- Extract patterns: what framing works, what language succeeds, what's the aesthetic register
- Identify the implicit selection criteria beyond the stated ones
- Output: `research/YYYY-MM-DD-<funder>-winners-analysis.md`

### Agent 3: Review Panel / Funder Intelligence
- Who reviews? How many? What backgrounds?
- What has the funder published about their values, priorities, recent strategic shifts?
- Annual reports, press releases, public statements
- Output: `research/YYYY-MM-DD-<funder>-panel-research.md`

### Agent 4: Competitor Landscape
- What similar projects have been funded? What's the field density?
- Where is the white space — what hasn't been done?
- Output: `research/YYYY-MM-DD-<funder>-landscape.md`

### Agent 5: Eligibility & Constraints Deep Read
- Every eligibility requirement, every constraint, every disqualification
- Disbursement rules (LLC? fiscal sponsor? individual only?)
- Timing constraints (premiere dates, completion dates)
- Output: added to `submission-checklist.md`

**All five agents run BEFORE any drafting begins.** The research informs the writing, not the other way around.

---

## Phase 2: RAW MATERIAL (First Revision — Handwritten / Free-Form)

Write the application in raw form. NOT in the character-limited fields. NOT in the final format. This is the nigredo — the prima materia.

- Write long. Write without counting characters.
- Write from the gut: why does this project need to exist? why now? why you?
- Use the research to ground every claim in evidence
- Reference past winners' patterns but don't copy their voice
- Let contradictions exist — they'll be resolved in revision

**The medium matters:** If writing by hand is possible, write by hand. The transcription into digital form IS the forced revision. If digital, write in a scratch file — NOT in draft.md. The move from scratch to draft IS the forced revision.

Artifacts:
- `scratch/raw-narrative.md` — unconstrained, long-form, messy
- `scratch/raw-questions.md` — each question answered without limits

---

## Phase 3: STRUCTURE (Second Revision — Forced Compression)

Take the raw material and compress it into the form's constraints. This is the albedo — the purification.

- Open `submission-checklist.md` and the raw material side by side
- For each field: extract from the raw, don't write from scratch
- Cut ruthlessly. Every word must earn its space.
- Write to CHARACTER COUNT from the start (not word count — characters include spaces)
- Strip all formatting — the form is plain text. No bold, no italics, no headers, no markdown.

Artifacts:
- `draft.md` — structured, character-counted, field-aligned

---

## Phase 4: VERIFICATION (Third Revision — Hall-Monitor Audit)

Dispatch the hall-monitor agent (or self-audit with extreme prejudice):

### Character Count Audit
- [ ] Every text field measured against its limit
- [ ] Every word-limited field measured by word count
- [ ] No field over limit. No field significantly under limit (wasted space = missed opportunity).

### Completeness Audit
- [ ] Every field in `submission-checklist.md` has content or a confirmed N/A
- [ ] Work sample prepared: file under 30 chars, within size limit, hosted (if video)
- [ ] Resume PDF created (art-only, concise)
- [ ] All uploads named and sized correctly

### Consistency Audit
- [ ] Project title matches across all mentions
- [ ] Statistics match across description, questions, and bio (repo count, test count, etc.)
- [ ] Tone is consistent — plain English, concrete, no jargon
- [ ] Claims in questions are supported by the description

### Legal/Constraint Audit
- [ ] Eligibility confirmed
- [ ] Completion date within allowed window
- [ ] Disbursement path is legal (individual vs LLC vs fiscal sponsor)
- [ ] No conflict with other applications (some funders have exclusivity)

---

## Phase 5: CITRINITAS (Fourth Revision — The Purification Read)

Read the ENTIRE application aloud. Every word. This is not editing — it's experiencing the application as the reviewer will. Does it flow? Does it convince? Does it sound like a human with a vision, not a system generating text?

Fix anything that sounds:
- Generic (could describe anyone's project)
- Jargon-heavy (systems theory terms without plain explanation)
- Defensive (justifying existence rather than asserting vision)
- Mechanical (listing features rather than painting a picture)

---

## Phase 6: SUBMISSION (Human-Gated)

- [ ] Open the web form in a desktop browser
- [ ] Paste each field from draft.md (plain text, stripped of markdown)
- [ ] Double-check character counts in the form's own counter
- [ ] Upload work sample, resume
- [ ] Complete all dropdown selections, checkboxes, demographic fields
- [ ] Screenshot the completed form before submitting
- [ ] Submit
- [ ] Save confirmation email/number
- [ ] Update IRF: mark application item as SUBMITTED with date

---

## Phase 7: POST-SUBMISSION (Archival + Reuse)

- Commit all application materials to the funder's directory
- Move research files to `research/` if not already there
- Update `submission-checklist.md` with final status
- If rejected: extract lessons into `research/YYYY-MM-DD-<funder>-post-mortem.md`
- If invited to Round II: prepare Round II materials per funder's specification
- If awarded: update IRF, update institutional strategy, celebrate

---

## Template Directory Structure

Every grant application gets this directory structure in `aerarium--res-publica/applications/`:

```
applications/<funder>-<year>/
├── README.md                  # Overview, deadline, status, IRF cross-ref
├── draft.md                   # The application text (character-counted, field-aligned)
├── bio.md                     # Bios tailored to this funder's lens
├── work-sample-notes.md       # Work sample selection, caption, hosting details
├── submission-checklist.md    # Complete field inventory + verification checklist
├── scratch/                   # Raw material (first revision)
│   ├── raw-narrative.md
│   └── raw-questions.md
└── materials/                 # Upload-ready files
    ├── resume.pdf
    └── work-sample/
```

---

## Agent Dispatch Prompts (Reusable)

### Research Prompt Template

```
Research the [FUNDER NAME] [GRANT/FELLOWSHIP/RESIDENCY] for the [YEAR] cycle.

1. Read the complete application handbook/guidelines at [URL]
2. Document EVERY form field with: name, type, character/word limit, format
3. Research 5-10 recent winners in [DISCIPLINE]. Extract: framing patterns, language that works, implicit criteria
4. Research the review panel: who reviews, how many, what backgrounds
5. Read the funder's recent annual reports, press releases, strategic priorities
6. Document all eligibility requirements and disbursement constraints
7. Identify the white space: what kind of project HASN'T been funded yet?

Output: field inventory, winners analysis, panel research, landscape analysis, constraint summary.
```

### Verification Prompt Template

```
Audit this grant application against the submission checklist.

1. Measure character count (including spaces) for every text field
2. Compare each count against the stated limit
3. Check every field in the submission checklist — is it filled or confirmed N/A?
4. Verify statistics are consistent across all mentions
5. Check all constraints (eligibility, dates, disbursement)
6. Flag any field over limit, any missing field, any inconsistency

Output: pass/fail per field, specific issues, recommended fixes.
```

---

## Principle

Each revision — raw → structured → verified → read-aloud → submitted — is a purification cycle. The application that reaches the form has been through four forced revisions. It is not what you wrote first. It is what survived. That is the method. That is how one thing is done well, and therefore how everything is done well.
