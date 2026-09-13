# PERW Changelog

## v1.2 — 2026-09-13

### MINOR change

PERW strengthens ChatGPT's explicit research-director architecture without changing the 12 stages, gate logic, identification order, scope rule, Stop Rule, or PI final authority.

### Added

- stage-specific Research Director / journal-review checkpoints;
- `protocols/research_director_review.md`;
- explicit R1 Identification Specialist, R2 Field Expert, and R3 Generalist / Editor reviews;
- BLOCKING / MAJOR / MINOR finding severity;
- the scientific-review handoff loop from ChatGPT specification through PI decision.

### Clarified

- ChatGPT is the default research-judgment and control layer and may directly complete research tasks it can perform to the required standard;
- heavy or repeated empirical execution remains the preferred domain of Codex/Hermes;
- Codex/Hermes may discover problems, challenge designs, and propose alternatives, but may not silently approve or implement major research-design changes;
- execution success does not establish scientific validity;
- existing papers may adopt v1.2 optionally and do not migrate automatically.

## v1.1 — 2026-09-13

### Major change

PERW is upgraded from a paper workflow into a multi-agent research operating system.

### Added

- explicit PI / ChatGPT / Codex / Hermes role architecture;
- `ROLE_ROUTING.md`;
- agent handoff protocol;
- execution specification protocol;
- execution report protocol;
- structural escalation protocol;
- independent replication protocol;
- new bootstrap files for ChatGPT, Codex, and Hermes Research Profile;
- minimal-load GitHub protocol through `CURRENT.md`;
- Workflow Update Governance for assessed, classified, and reversible PERW improvement;
- rule that new projects use current stable PERW while ongoing projects do not silently migrate across breaking changes.

### Clarified

ChatGPT is not limited to topic discussion. It may act as Research Director, Co-Researcher, internal editor, literature/policy/web researcher, identification critic, evidence synthesizer, journal-positioning adviser, and task orchestrator.

Codex and Hermes primarily execute and audit research designs. They may identify design failures but may not silently redefine the research question, treatment, estimand, primary outcome, or identifying assumption.

### PATCH

- Corrected Hermes research-profile routing from “Study Profile” to “Research Profile”; no change to agent authority or research workflow.

### v1.0 baseline

v1.0 introduced the Core Question / Identified Claim / Paper Scope distinction, staged research workflow, parallel Stage-0 gates, stop/reopen rules, scope-change discipline, and reviewer pre-mortem.
