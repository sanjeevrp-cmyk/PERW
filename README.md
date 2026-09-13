# PERW — Personal Empirical Research Workflow

PERW is a personal research operating system for empirical finance/economics papers.

It is designed to be read automatically by:
- **ChatGPT** — Research Director / Research Architect / Co-Researcher / Internal Editor / Evidence Integrator
- **Codex** — Primary Empirical Research Engineer / Data Auditor
- **Hermes Research Profile** — Empirical Research Engineer / Independent Analyst / Auditor

PERW stores **how research should be conducted**. It does **not** store individual paper projects, unpublished ideas, private data, empirical results, or submission files.

## Intended research standard

Default use:
- empirical finance / corporate finance / fintech / technology finance;
- SSCI Q2 or better as the practical target;
- moderate workload;
- obtainable data;
- credible identification;
- willingness to stop weak projects instead of rescuing them with method stacking.

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

**divergence → candidate comparison → parallel feasibility gates → claim/scope freeze → identification → data engineering → primary evidence → threat-mapped robustness → mechanism → claim ladder → writing → adversarial review**

ChatGPT provides stage-specific research-judgment checkpoints through `protocols/research_director_review.md`; these checkpoints do not alter the 12-stage structure or existing gate, identification, scope, and stop rules.

The system separates:
- **Core Question**
- **Identified Claim**
- **Paper Scope**

Failure of one dataset or one design is not automatically failure of the Core Question.

## How agents should use the repo

Agents should first read `CURRENT.md`, then load the current workflow and role rules. They should not reload the whole repository for every message.

If GitHub access is unavailable, an agent must say so and request the workflow file or repo URL rather than pretending it loaded PERW.
