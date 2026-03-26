---
name: NLnet scoring criteria and adversarial review findings
description: Key lessons from 3-persona adversarial review of NLnet application — what almost killed the score and how it was fixed
type: project
---

NLnet NGI0 Commons Fund scores on three criteria (must exceed 5.0/7.0):
- Relevance / impact / strategic potential: **40%** weight
- Technical excellence / feasibility: **30%**
- Cost effectiveness / value for money: **30%**

**Critical findings from S38 adversarial review (pre-revision score: 3.96/7.0):**

1. No NGI alignment language = near-disqualifying (40% of score is relevance)
2. European Dimension unaddressed = disqualifying for non-EU applicants
3. Overstating technical claims (e.g., "multiplex DAG" when only 2/4 flow types populated) = technical reviewers will verify against code
4. Mentioning commercial model in a commons infrastructure application = red flag
5. No evidence of external demand or community = "who else cares?"
6. License contradictions (MIT in code vs Apache 2.0 in application) = sloppiness signal

**What fixed it:** NGI language throughout, publiccode.yml + REUSE (EU standards), honest coupling analysis, dogfooding sustainability (not commercial), concrete numbers (150K+ orgs, KDE/GNOME/CERN named), explicit R&D question.

**How to apply:** Any future NLnet or EU-funded application must address European Dimension explicitly, name NGI, reference EU-originated standards, and never mention commercial revenue in the commons-facing narrative.
