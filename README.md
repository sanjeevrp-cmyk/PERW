# PERW — Personal Empirical Research Workflow

PERW is a personal research operating system for high-quality empirical economics, management, finance, and related research.

Current stable release: **v2.8**.

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

## Key design

Research proceeds through:

**problem discovery → candidate architecture → routed feasibility gates → claim/scope freeze → evidence and identification blueprint → data/measurement engineering → primary evidence → threat-mapped robustness → mechanism → claim ladder → writing → adversarial review**

ChatGPT provides stage-specific research-judgment checkpoints through `protocols/research_director_review.md`. Universal gates protect contribution, data/measurement quality, and claim-architecture fit; conditional gates protect causal, viewpoint-guided, measurement/new-fact, and regional/spatial claims.

`protocols/research_genesis_branch_governance.md` preserves scientific origin in `templates/RESEARCH_GENESIS_ANCHOR.md` and parent history in `templates/RESEARCH_BRANCH_REGISTRY.md`. Qualitative object fingerprints distinguish implementation/design repair, extension, new branches, and replacement. Literature attacks novelty through a multidimensional collision audit without silently replacing the question. Causal ambition is intent, not a causal claim, and requires explicit assessment/resolution rather than silent downgrade. The anchor is not a design freeze, weak branches may be killed, and no universal novelty score exists. Scope freeze, Gate criteria, causal standards, Stop / Reopen rules, and actual agent authority are unchanged; ongoing projects require separate adoption/migration assessment.

Data access follows `protocols/data_access_handoff.md`: executors autonomously obtain lawfully accessible data, restricted sources trigger a precise PI handoff, and executor access failure never substitutes for a scientific Data / Measurement Gate judgment.

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

If GitHub access is unavailable, an agent must say so and request the workflow file or repo URL rather than pretending it loaded PERW.
