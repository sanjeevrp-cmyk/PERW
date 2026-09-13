# PERW v1.2 — Personal Empirical Research Workflow

## Stage 0 — Goal Lock
Record target discipline/journal tier, publication speed versus ceiling, acceptable workload, available databases, unavailable/private-data constraints, time horizon, and execution capacity.

## Stage 1 — Divergent Sprint
Before feasibility criticism collapses the idea: generate ≥3 economic questions, ≥3 candidate outcomes/estimands, ≥2 identification routes, rival explanations, and cross-literature connections. No formal regressions.

**Research Director checkpoint:** apply the Stage 0–1 Research Architect / Co-Researcher review in `protocols/research_director_review.md`.

## Stage 2 — Candidate Cards
For each candidate record Core Question, friction, shock/policy, assignment, estimand, outcome, data, closest literature, rival explanation, identification threat, workload, journal ceiling, and cheapest kill test. Compare before commitment.

## Stage 3 — Parallel Stage-0 Gates
Run Competition Gate, Policy/Assignment Gate, and Data/Count Gate in parallel. Decisions: GO / GO WITH REPAIR / HOLD / NO-GO. No formal causal regression before the gates support proceeding.

## Stage 4 — Scope & Claim Contract
Freeze Core Question, Identified Claim, Paper Scope, unit, treatment, primary outcome, estimand, comparison group, identifying assumption, sample window, primary falsification tests, and prohibited causal language. Major later changes require a Scope Change Memo.

## Stage 5 — Identification Blueprint
Mandatory order: assignment → counterfactual → estimand → identifying assumption → estimator → inference → diagnostics → falsification. Identification must survive a reviewer-facing pre-mortem.

**Research Director checkpoint:** apply the Stage 2–5 Research Director + SSCI Q2+ Shadow Referee review.

## Stage 6 — Data Engineering & Pre-analysis Freeze
Build data dictionary, raw-to-clean pipeline, sample funnel, event/entity IDs, treatment audit, variable-construction log, missingness audit, and reproducible master script. Where feasible, freeze primary sample/outcome/specification before result-driven iteration.

## Stage 7 — Main Evidence
Estimate the primary estimand first. Interpret sign, uncertainty, economic magnitude, estimand population, and connection to frozen claim. If it fails, distinguish true null, low power, measurement failure, treatment misclassification, and invalid design. Do not outcome-shop.

## Stage 8 — Threat-Mapped Robustness
Every test must name the threat it addresses: differential pre-trends, staggered treatment, contamination, spillovers, treatment misclassification, single-region dominance, alternative measurement, bank-specific marketing, etc.

## Stage 9 — Mechanism and Rival Explanations
Mechanisms follow the main effect. Prefer tests that distinguish favored channel A from plausible rival B. Avoid mechanical mediation unless causal requirements are credible.

## Stage 10 — Claim Ladder
Classify the strongest supported statement: descriptive fact → association → causal effect → causal mechanism → external generalization. Do not claim above the supported level.

**Research Director checkpoint:** apply the Stage 6–10 Research Director / Evidence Integrator review.

## Stage 11 — Writing
Recommended order: institution/background → data → empirical strategy → main results → robustness → mechanisms → conclusion → introduction → abstract. Verify citations, avoid invented references, keep abstract claims within evidence, and leave unresolved facts as TODO.

## Stage 12 — Adversarial Review
Use R1 Identification Specialist, R2 Field Expert, and R3 Generalist/Editor. Classify blocking/major/minor comments. Do not recommend submission while blocking comments remain.

**Research Director checkpoint:** apply the Stage 11–12 Internal Editor + SSCI Q2/Q1 Referee review.

## Stop rule
Stop/HOLD if treatment cannot be recovered, outcome does not measure intended estimand, treated support is structurally insufficient, contribution is occupied, counterfactual is invalid, concurrent policy destroys identification, or essential data are unavailable.

## Reopen rule
Reopen only when new evidence changes a blocking condition.

## Scope-change rule
If treatment, estimand, primary outcome, sample population, identifying assumption, or causal claim changes, explicitly audit the scope change before treating the revised design as the same project.
