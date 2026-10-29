---
status: proposed | accepted | superseded-by-NNNN | deprecated
date: YYYY-MM-DD
review-by: YYYY-MM-DD
deciders: [name]
reversibility: two-way-door | one-way-door
confidence: low | medium | high
tags: [caching, resilience]
---

<!--
Copy to adr/NNNN-short-title.md.
Two-way-door decision? Use templates/adr-template-light.md instead.
Sections marked HUMAN-WRITTEN are yours: do not let an AI draft them.
-->

# ADR-NNNN: <short noun phrase describing the decision>

## 1. Decision to be made
One sentence: "Which X should we use for Y, given Z?"

Concept notes: <Notion links>

## 2. Context and drivers  <!-- HUMAN-WRITTEN -->
- Situation (3-5 lines, real constraints, not generic):
- Quality attribute scenarios:

| Source | Stimulus | Response | Measure |
|--------|----------|----------|---------|

- Constraints (team skills, budget, compliance, deadline, existing stack):
- Assumptions (believed, not yet verified):
- Non-goals:

## 3. Options considered
| Option | Summary | Pros | Cons | Verdict |
|--------|---------|------|------|---------|
| 0. Do nothing / simplest thing | | | | |
| A. | | | | |
| B. | | | | |

Why each rejected option lost (one line each):

## 4. Decision  <!-- HUMAN-WRITTEN -->
We will ___ because ___ (reference the drivers above).

## 5. Consequences
- Positive:
- Negative / risks we knowingly accept:

## 6. Impact on quality attributes
| Attribute | Impact (↑ ↓ →) | Notes |
|-----------|----------------|-------|
| Consistency | | |
| Latency | | |
| Availability | | |
| Cost | | |
| Security | | |
| Team complexity / cognitive load | | |
| Operability | | |

## 7. Failure modes and blast radius
Include the "slow, not dead" case.

| Failure | Likelihood | Blast radius | Detection | Degradation / mitigation |
|---------|------------|--------------|-----------|--------------------------|

## 8. Reversibility
- Door type and why:
- Cost to reverse (time, data migration, contracts, retraining):
- Point of no return:
- Exit path:

## 9. Operations
- Owner / on-call team:
- Signals (alerts, dashboards, logs):
- What the 3 a.m. page looks like, and the runbook link:
- Ongoing toil:

## 10. Validation
| Metric | Target | How measured | Where |
|--------|--------|--------------|-------|

- Fitness function: `fitness-functions/...`
- Lab evidence: `labs/...`

## 11. Revisit triggers
Concrete conditions (e.g. "p95 > 200 ms for 7 days", "10x traffic", "cost > €X/month").
Each trigger should map to an assumption in section 2.

## 12. Open questions and risks

## 13. AI involvement
| Stage | Model/tool | What I asked | What it changed | How I verified |
|-------|-----------|--------------|-----------------|----------------|

## 14. Links
Diagrams, related ADRs, supersedes / superseded-by, references.
