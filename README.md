# ArchitectureWorkout

Practice ground for my solution-architect journey. Theory lives in Notion; decisions and evidence live here.

```
Concept (Notion)  →  Decision (ADR)  →  Evidence (lab, fitness function, diagram)
```

- Every ADR links to the Notion concept page it relies on.
- Every Notion concept page ends with a "Where I applied this" section linking back to folders here.
- A concept with no ADR or lab behind it is still just reading.

## Layout

| Folder | Purpose |
|--------|---------|
| [`adr/`](adr/) | Architecture Decision Records (MADR-inspired) |
| [`diagrams/`](diagrams/) | C4 as code (Structurizr DSL / Mermaid) |
| [`fitness-functions/`](fitness-functions/) | ArchUnit tests, SLO checks, notes |
| [`tradeoffs/`](tradeoffs/) | Comparisons and ATAM-lite analyses |
| [`quality-scenarios/`](quality-scenarios/) | NFRs written as measurable scenarios |
| [`labs/`](labs/) | One hands-on folder per concept |
| [`case-studies/`](case-studies/) | "Design X" exercises with capacity estimates |
| [`communication/`](communication/) | The same decision explained to engineers vs a CTO |
| [`ai-harness/`](ai-harness/) | Prompts and logs for using AI in decision-making |
| [`templates/`](templates/) | ADR (full and light) and quality-scenario templates |

## Concept map (Notion)

Notion root: [Concepts](https://app.notion.com/p/30d9bb0e7ea780b8ad8ff959240f2c1f)

| Concept | Notion | Notion status | ADR | Lab |
|---------|--------|---------------|-----|-----|
| Load Balancing | [page](https://app.notion.com/p/30d9bb0e7ea780309181daa788bdc8b6) | detailed | – | – |
| Caching | [page](https://app.notion.com/p/30d9bb0e7ea780cbbcf1e2baa898b0aa) | detailed (older duplicate to retire) | – | – |
| Content Delivery Networks | [page](https://app.notion.com/p/30d9bb0e7ea78062ab0bce0c59a031d8) | good | – | – |
| Messaging Queue & Pub-Sub | [page](https://app.notion.com/p/30d9bb0e7ea78011aec4ed0b3563cc72) | good (overlaps Publish-Subscribe) | – | – |
| Publish-Subscribe | [page](https://app.notion.com/p/30d9bb0e7ea7801bac4ccbf87a1b2187) | detailed | – | – |
| API Gateways | [page](https://app.notion.com/p/30d9bb0e7ea780149043d57cab26a780) | detailed | – | – |
| Circuit Breaker | [page](https://app.notion.com/p/30d9bb0e7ea78071833cd7cd4bf8156a) | empty | – | – |
| Service Discovery | [page](https://app.notion.com/p/30d9bb0e7ea780c68587f111e12ad993) | empty | – | – |
| Sharding | [page](https://app.notion.com/p/30d9bb0e7ea780c2b3a0ff742a547f00) | empty | – | – |
| Rate Limiting | [page](https://app.notion.com/p/30d9bb0e7ea780d3aca5c16f18c9de01) | empty | – | – |
| Consistent Hashing | [page](https://app.notion.com/p/30d9bb0e7ea78070b230d050e67f8bc0) | empty | – | – |
| Auto Scaling | [page](https://app.notion.com/p/30d9bb0e7ea780d8808cf476f8a0a6c4) | stub | – | – |

Not yet reviewed: Databases, Application Practices, Microservice Patterns, Monolith vs Microservices, Snowflake.

## Working rules

1. Write quality scenarios before choosing technology.
2. Scale ceremony to reversibility: light ADR for two-way doors, full ADR for one-way doors.
3. Treat every number and API claim as unverified until a lab or primary documentation confirms it.
4. Context and decision sections of an ADR are written by me; AI involvement is logged.

## Status

Phase 1 (foundation) in progress. Next: the Caching vertical slice (lab, ADR, failure drill, fitness function).
