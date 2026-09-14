# PERW — Personal Empirical Research Workflow

PERW is a personal research operating system for high-quality empirical economics, management, finance, and related research.

Current stable release: **v2.0**.

It is designed to be read automatically by:
- **ChatGPT** — Research Director / Research Architect / Co-Researcher / Internal Editor / Evidence Integrator
- **Codex** — Primary Empirical Research Engineer / Data Auditor
- **Hermes Research Profile** — Empirical Research Engineer / Independent Analyst / Auditor

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
