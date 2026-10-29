# AI harness

Scaffolding that keeps AI useful in architecture decisions: defined roles, structured inputs, human gates.

- `prompts/`: reusable prompts per stage (options, trade-offs, red team, pre-mortem, failure modes, communication, review)
- `review-log.md`: where AI changed, or did not change, a decision
- `failure-cases.md`: times AI was confidently wrong, and how it was caught

Principles: I write context and decision myself; I form a view before asking; AI plays adversary, not oracle;
numbers and API claims stay unverified until a lab or primary source confirms them; involvement is logged in ADR section 13.
