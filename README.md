# PERW — Personal Empirical Research Workflow

PERW is a personal research operating system for high-quality empirical economics, management, finance, and related research.

Current stable release: **v2.11** (MINOR).

v2.11 clarifies [Skills admission and routing](protocols/research_skill_routing.md): four admission decisions with evidenced dispositions, three permitted HOLD reasons, same-task replacement comparisons, and method distillation in existing skills/checks. Already-distilled baselines cannot establish no incremental value; adoption is separate from project discoverability, and derived views grant no admission authority. See [CURRENT](CURRENT.md) and [release notes](CHANGELOG.md#v211--2026-10-20).

Research Skills implicit AUTO remains **NOT_PROVEN**. Verified evidence covers project-level discovery and bounded local **PINNED** application, not implicit host selection or scientific validity. Scientific authority and Stage/Gate rules are unchanged; active papers do not migrate automatically.

It is designed to be read automatically by:
- **ChatGPT** — Research Director / Scientific Question Guardian / Research Architect / Identification Strategist / Literature Adversary / Evidence Integrator / Internal Editor
- **Codex** — Primary Empirical Research Engineer / Data & Measurement Auditor / Identification Implementation Engineer / Reproducibility Owner
- **Hermes Research Profile** — Independent Scientific Auditor / Scope-Drift Auditor / Adversarial Identification Auditor / Novelty-Collision Auditor / Independent Replicator / Construct & Provenance Auditor

These names clarify responsibilities without changing authority. The PI remains Principal Investigator / Research Direction Owner / Final Scientific Authority. ChatGPT retains scientific review and recommendation, Codex approved implementation, and Hermes independent audit and approved execution.

PERW stores **how research should be conducted**. It does **not** store individual paper projects, unpublished ideas, private data, empirical results, or submission files.

## Intended research standard

Default use:
- applied economics, management, regional and industrial economics, development, public and political economy, finance, and related fields;
- SSCI Q2 or better as the practical target;
- scientifically meaningful questions and credible evidence;
- moderate or justified workload;
- obtainable data;
- evidence architecture matched to the intended claim;
- full identification standards whenever a causal claim is made;
- willingness to stop weak projects instead of rescuing them with method stacking.

High-level domestic and international journals may serve as scientific-question, literature, and paper-architecture benchmarks without becoming mandatory submission targets.

## Repository architecture

```text
PERW/
├── CURRENT.md
├── README.md
├── CHANGELOG.md
├── core/
│   ├── PRINCIPLES.md
│   ├── WORKFLOW.md
│   └── ROLE_ROUTING.md
├── stages/
├── gates/
├── protocols/
├── templates/
└── bootstrap/
```

## Authority and navigation

Read CURRENT first, then the three core files and only the task-relevant entries. The layers below divide responsibilities; they do not require moving directories or building another Agent platform. Paths in code spans are repository-root-relative.

| Object | Authoritative source | Supporting records and boundary |
|---|---|---|
| Version selection | [CURRENT](CURRENT.md#agent-loading-rule); [update governance](protocols/workflow_update_governance.md) | Use an ongoing project's recorded version; a new central release does not migrate it. |
| Scientific principles and Agent authority | [PRINCIPLES](core/PRINCIPLES.md); [ROLE_ROUTING](core/ROLE_ROUTING.md) | PI final authority, ChatGPT scientific review, Codex approved implementation, Hermes independent audit/approved execution remain unchanged. Bootstrap files are loading summaries. |
| Stage 0–12 and conditional Gates | [WORKFLOW](core/WORKFLOW.md); the applicable files in gates/ | stages/ entries are task guidance. Gate routing and passing criteria remain scientific rules, not runtime status. |
| Genesis, Branch, Scope and escalation | [Genesis/Branch governance](protocols/research_genesis_branch_governance.md); [Stage 4](stages/04_scope_contract.md); [escalation](protocols/escalation_protocol.md) | The paper workspace holds its own Genesis, Branch, formal Scope and decisions. Runtime state must reference these rather than create a second scientific CURRENT. |
| Skills and runtime capability | [skill routing](protocols/research_skill_routing.md); [method/runtime readiness](protocols/method_runtime_readiness.md) | The actual approved registry/source locks and host execution evidence live in the authorized runtime/project. Published, approved, discovered, guidance used, function executed and validated behavior are distinct; discovery does not prove automatic selection. |
| Data operations and measurement validity | [Stage 6 routing](stages/06_data_engineering.md#three-class-data-operation-routing); [risk-based validation](protocols/risk_based_measurement_validation.md) | Project sources, construction rules, sample accounting and validation records supply the evidence. Routine transformations do not waive measurement or Scope safeguards. |
| Execution, completion and evidence reuse | [execution specification](protocols/execution_spec.md#task-completion-and-verification-reuse); [handoff](protocols/agent_handoff.md) | The current authorized task sets outputs and acceptance criteria. Existing reports/checkpoints hold evidence; no new mandatory ledger or report is required. Task completion does not pass a scientific Gate. |
| Evidence to manuscript | [publication architecture](protocols/econ_management_publication_architecture.md) | Project data/code/results, exhibits and manuscript claims keep their authoritative links; verify results before claims. |

Stage 0 is defined in core/WORKFLOW.md; there is no separate stages/00 file. The historical filename stages/03_stage0_gates.md now contains Stage 3 Routed Feasibility Gates. stages/05_identification.md contains the Evidence & Identification Blueprint for causal and noncausal designs. These paths remain unchanged for existing references.

The PERW core owns general scientific rules; Research OS runtime support owns approved component/host routing and task continuity; each paper workspace owns its scientific state, sources, code, results and manuscript. A runtime capability/evidence index is a navigation view of dated records, not another registry, live host certification or scientific decision-maker.

## Key design

Research proceeds through:

**problem discovery → candidate architecture → routed feasibility gates → claim/scope freeze → evidence and identification blueprint → data/measurement engineering → primary evidence → threat-mapped robustness → mechanism → claim ladder → writing → adversarial review**

ChatGPT provides stage-specific research-judgment checkpoints through `protocols/research_director_review.md`. Universal gates protect contribution, data/measurement quality, and claim-architecture fit; conditional gates protect causal, viewpoint-guided, measurement/new-fact, and regional/spatial claims.

`protocols/research_genesis_branch_governance.md` preserves scientific origin in `templates/RESEARCH_GENESIS_ANCHOR.md` and parent history in `templates/RESEARCH_BRANCH_REGISTRY.md`. Qualitative object fingerprints distinguish implementation/design repair, extension, new branches, and replacement. Literature attacks novelty through a multidimensional collision audit without silently replacing the question. Causal ambition is intent, not a causal claim, and requires explicit assessment/resolution rather than silent downgrade. The anchor is not a design freeze, weak branches may be killed, and no universal novelty score exists. Scope freeze, Gate criteria, causal standards, Stop / Reopen rules, and actual agent authority are unchanged; ongoing projects require separate adoption/migration assessment.

Data access follows `protocols/data_access_handoff.md`: executors autonomously obtain lawfully accessible data, restricted sources trigger a precise PI handoff, and executor access failure never substitutes for a scientific Data / Measurement Gate judgment.

High-risk core construction follows `protocols/risk_based_measurement_validation.md`: validate scientific objects and actual rules with source-backed stress cases before scaling; distinguish replication, blind spot checks, non-blind adversarial audit, and evidence adjudication; allow asymmetric work while preserving necessary blind review and common-error discovery. Key rule changes trigger dependency-based revalidation/recomputation, with verified reuse of unaffected artifacts. Agent agreement is not truth, and unverified old results cannot support current claims. No new Gate, authority, fixed audit quota, mandatory tool, or automatic active-project migration is introduced.

Stage 1–2 candidate development follows `protocols/early_data_feasibility.md`: after independent scientific divergence, candidates about to receive substantial further effort distinguish required, observable, and missing evidence; audit both core-construct and primary-evidence observability; record qualitative Data Risk; and run the cheapest proportionate feasibility test. This allocates research effort and does not replace the Stage 3 Data / Measurement Gate.

Major scientific decisions follow `protocols/high_quality_literature_anchoring.md`: maintain a verified, role-specific benchmark map; search seriously for the closest paper and current frontier; translate literature into generalizable logic and design fit; and verify any formal Q1/Q2 claim by named ranking system, year, and relevant category. Prestige and citation count never substitute for scientific importance, identification, evidence, or residual contribution.

Stage 11–12 manuscript work follows `protocols/manuscript_argument_integrity.md`: lead with supported claims, retain material limits and unfavorable evidence, and review the exact submission deliverable.

Nontrivial research tasks follow `protocols/research_skill_routing.md`: inspect only skills actually available, select the smallest useful set, and reject any instruction that conflicts with PERW, the frozen paper design, or the approved execution specification. External skills are optional aids, not scientific authority.

Before materially nontrivial claim-bearing formal estimation or inference, `protocols/method_runtime_readiness.md` checks method fit, data and support, temporal provenance, runtime capability, and a proportionate validation run. Scientific role is separate from execution readiness; failures normally remain local to the affected branch, and no estimator, software package, skill, or universal numerical threshold is mandatory.

Stages 7–11 use `protocols/econ_management_publication_architecture.md` to connect verified results to main-text exhibits, appendix/supplement material, replication artifacts, and manuscript sentences. Each main exhibit has one primary scientific job, headline numbers retain authoritative provenance, and result verification precedes claim verification.

Research-code implementation follows `protocols/research_code_economy.md`: use the simplest implementation that preserves scientific checks, provenance, and reproducibility. Simplicity does not mean the fewest lines of code. Optional code-economy skills are never required.

The system separates:
- **Core Question**
- **Claim Type**
- **Identified Claim**
- **Evidence Architecture**
- **Paper Scope**

Failure of one dataset or one design is not automatically failure of the Core Question.

## How agents should use the repo

Agents should first read `CURRENT.md`, then load the current workflow and role rules. They should not reload the whole repository for every message.

Follow [GitHub loading and verified-cache fallback](protocols/github_loading.md). Disclose failed live access and the exact version/provenance of any previously verified cache; a cache is not evidence of the current online release.
