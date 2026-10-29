# QS-NNN: <short name>

Copy to `quality-scenarios/QS-NNN-short-name.md`. Write the scenario before choosing any technology.

| Field | Value |
|-------|-------|
| Quality attribute | latency / availability / consistency / scalability / security / ... |
| Source | Who or what generates the stimulus |
| Stimulus | What happens |
| Artifact | Which part of the system is stimulated |
| Environment | Normal load, peak, degraded, during deploy, ... |
| Response | What the system must do |
| Response measure | A number: p95 < 100 ms at 5k RPS, stale reads <= 60 s, RTO <= 15 min |

Example: "Under peak load (5k RPS), a product-page read returns in p95 < 100 ms, and data up to 60 s stale is acceptable."

Used by: <ADR links>
Verified by: <fitness function or lab link>
