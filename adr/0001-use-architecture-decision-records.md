---
status: proposed
date: 2026-10-29
review-by: 2027-04-29
deciders: [Oguzhan Turan]
reversibility: two-way-door
confidence: medium
tags: [process, adr]
---

<!-- DRAFT: sections 2 and 4 are HUMAN-WRITTEN. Rewrite them in your own words before accepting. -->

# ADR-0001: Record architecture decisions as ADRs in this repository

## 1. Decision to be made
How do I turn architecture reading (Notion) into decisions that can be challenged and revisited?

## 2. Context and drivers  <!-- HUMAN-WRITTEN -->
- Situation: Concept notes live in Notion; this repository starts empty. Reading alone does not build the habit of deciding, trading off and validating.
- Drivers: decisions must be explicit, challengeable and tied to evidence; the habit must stay sustainable.
- Constraints: part-time effort, solo learner, no team to review.
- Assumptions: a small, consistent template will be used; ceremony scaled to reversibility will keep it light enough.
- Non-goals: ADRs for every tiny choice; replacing Notion as the home of concept notes.

## 3. Options considered
| Option | Summary | Pros | Cons | Verdict |
|--------|---------|------|------|---------|
| 0. Notes only (Notion) | Keep reading and writing concept pages | Zero new process | No decisions, no evidence, no revisit | Rejected |
| A. Free-form decision notes | Ad hoc markdown | Low friction | Inconsistent, hard to search or review | Rejected |
| B. ADRs (MADR-inspired template) | One file per decision, versioned in git | Searchable, reviewable, tied to labs | Some ceremony | Chosen |

## 4. Decision  <!-- HUMAN-WRITTEN -->
Use ADRs in `adr/`, with the full template for one-way doors and the light template for two-way doors, because the goal is practising decisions, not collecting knowledge.

## 5. Consequences
- Positive: decisions have context, alternatives and revisit triggers; Notion concepts gain links to evidence.
- Negative: writing overhead; a risk of template fatigue.

## 8. Reversibility
Two-way door. ADRs are plain markdown; dropping the practice costs nothing but the habit.

## 11. Revisit triggers
- I stop writing ADRs for 6 weeks (template too heavy: simplify it).
- ADRs are written but never linked to a lab or fitness function (they have become paperwork).

## 13. AI involvement
| Stage | Model/tool | What I asked | What it changed | How I verified |
|-------|-----------|--------------|-----------------|----------------|
| Draft | Claude | Draft a starting version of this ADR | Wrote the first draft | Rewrite sections 2 and 4 myself |

## 14. Links
- Template: `templates/adr-template.md`, `templates/adr-template-light.md`
- Concept notes: Notion "Concepts" page (see README)
