# PERW Changelog

## v2.2 — 2026-09-17

### MINOR change

PERW strengthens Stage 11 manuscript argument and Stage 12 referee review with claim-forward, evidence-bounded writing. It adds `protocols/manuscript_argument_integrity.md`, lightweight writing contracts, two-way claim–evidence alignment, change-impact synchronization, and exact-deliverable review. R3 now checks argument and prose integrity, including hidden unfavorable evidence and post-hoc story drift.

Stage 0–10 architecture, Gate decisions, scientific and causal standards, frozen scope, Stop/Go rules, and agent research authority are unchanged. Active papers may optionally adopt v2.2 at Stage 11–12 without redesign; no project migrates automatically.

## v2.1 — 2026-09-15

### MINOR change

PERW adds a data-access and PI-handoff workflow that separates executor permissions from team data availability and scientific data validity.

### Added

- `protocols/data_access_handoff.md` with agent-first acquisition, restricted-access pause, branch-level continuation, validation, and checkpoint-resume rules;
- standard states: AUTO_ACCESSIBLE, ACCESS_BLOCKED_PI_REQUIRED, DELIVERED_PENDING_VALIDATION, VALIDATED, and TRULY_UNAVAILABLE;
- `templates/PI_DATA_REQUEST.md` for precise restricted-data requests.

### Clarified

- executor access failure is not PI access failure, team unavailability, measurement failure, or design failure;
- a restricted-access pause keeps the Data / Measurement Gate pending rather than causing NO-GO;
- only team-level legal unavailability or genuine unobservability supports the existing data-unavailability Stop condition;
- Codex and Hermes autonomously acquire lawfully accessible data, never request credentials or bypass controls, validate PI-delivered files, and resume from the recorded checkpoint;
- Stage structure, scientific Gate criteria, causal identification standards, and agent research authority are unchanged.

Active papers may adopt v2.1 without migrating frozen research-design objects.

## v2.0 — 2026-09-14

### BREAKING change

PERW becomes a multi-architecture empirical research workflow. It no longer treats a policy/shock causal design as the universal starting point, while preserving the full identification standard for every causal claim.

### Changed

- broadened the research domain to high-quality empirical economics, management, finance, and related fields;
- redesigned Stage 0–5 around research genesis, Claim Type, Evidence Architecture, routed gates, and an Evidence & Identification Blueprint;
- generalized Stage 6–10 for measurement, viewpoint-guided, descriptive, spatial, network, and causal evidence;
- replaced universal treatment-based stop conditions with universal and causal-conditional rules;
- generalized role, handoff, replication, escalation, and execution-spec language without changing PI/ChatGPT/Codex/Hermes authority.

### Added

- universal Research Architecture Fit Gate;
- conditional Proposition / Rival-Discrimination, Construct Validity, and Geographic Scope / Spatial Validity Gates;
- Viewpoint-to-Evidence Protocol;
- Paper Architecture Reverse-Engineering Protocol.

### Preserved

- Stage 0–12 structure;
- **Paper Scope ≤ Identified Claim ≤ Evidence**;
- full causal sequence: assignment → counterfactual → estimand → identifying assumption → estimator → inference → diagnostics → falsification;
- scientific-value, divergence, cheap-information, threat-mapped robustness, no-significance-hunting, no-complexity-rescue, reproducibility, independent-verification, and critical-collaboration principles;
- PI final authority and executor design boundaries.

Archived projects do not migrate automatically. A reopened project requires a separate PERW migration assessment.

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
