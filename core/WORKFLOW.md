# PERW v2.3 — Personal Empirical Research Workflow

## Stage 0 — Goal & Research Domain Lock
Record target journal tier, publication speed versus ceiling, acceptable workload, available databases, execution capacity, broad disciplinary domain, allowable evidence architectures, time horizon, and any geographic-scope constraints. The default publication goal is SSCI Q2 or better; do not lock the project into a single substantive field.

## Stage 1 — Problem Discovery & Divergent Sprint
Use theory/viewpoint-led, literature/puzzle-led, policy/institution-led, data/measurement-led, and regional/spatial phenomenon-led research genesis. Generate multiple non-equivalent Core Questions, propositions, mechanisms, rivals, outcomes/constructs, and evidence architectures. Convert viewpoints into falsifiable predictions; extract architecture from high-level papers without copying their setting or method. No formal regressions.

**Research Director checkpoint:** apply the Stage 0–1 Research Architect / Co-Researcher review in `protocols/research_director_review.md`.

## Stage 2 — Candidate Architecture
For each candidate record research genesis, Core Question, scientific importance, Claim Type, mechanism, proposition/prediction, Evidence Architecture, setting/geography rationale, key construct, primary evidence, data, closest literature and paper architecture, residual contribution, main rival, main validity threat, workload, journal ceiling, and cheapest kill test. Policy/shock, assignment, counterfactual, estimand, and identifying assumption are mandatory only for causal claims or causal-policy designs.

## Stage 3 — Routed Feasibility Gates
Every candidate must pass the Competition / Contribution Gate, Data / Measurement Gate, and Research Architecture Fit Gate. Route conditional gates by Claim Type and Evidence Architecture: causal claims use Policy / Assignment when relevant and the mandatory Identification Gate; viewpoint/theory-guided claims use Proposition / Rival-Discrimination; measurement/new-fact claims use Construct Validity; regional/spatial claims use Geographic Scope / Spatial Validity. Other architectures require an explicit design-specific validity check approved by ChatGPT/PI. Decisions remain GO / GO WITH REPAIR / HOLD / NO-GO. If executor access is blocked but team availability is unresolved, the Data / Measurement Gate remains PENDING rather than failing. No expensive full execution before the relevant gates support proceeding.

## Stage 4 — Scope & Claim Contract
Freeze Core Question, Claim Type, Identified Claim, Paper Scope, Evidence Architecture, unit, geographic scope, key construct, primary outcome/evidence, main rival explanation, evidence standard, sample window, primary falsification/validation tests, and prohibited claim language. For causal papers also freeze treatment, assignment, counterfactual, estimand, comparison group, and identifying assumption. Major later changes require a Scope Change Memo.

## Stage 5 — Evidence & Identification Blueprint
Universal order: **Core Question → Claim Type → Key Construct → Required Evidence → Rival Explanations → Evidence Architecture → Inference → Diagnostics → Falsification / Validation**. Use architecture-specific evidence standards. For causal claims, additionally preserve the mandatory sequence: **assignment → counterfactual → estimand → identifying assumption → estimator → inference → diagnostics → falsification**. Causal identification must survive a reviewer-facing pre-mortem.

**Research Director checkpoint:** apply the Stage 2–5 Research Director + SSCI Q2+ Shadow Referee review.

## Stage 6 — Data & Measurement Engineering / Pre-analysis Freeze
Build a data dictionary, provenance record, raw-to-clean pipeline, sample funnel, entity/event/geographic IDs, construct and measurement validation, variable-construction log, missingness audit, and reproducible master script. Support text-derived measures, geographic/spatial data, network data, constructed indices, and administrative/firm/city matching when relevant. For causal designs, also audit treatment. Follow `protocols/data_access_handoff.md` for autonomous acquisition, restricted-access pauses, PI delivery, validation, and checkpoint resume. Where feasible, freeze primary sample, evidence, and specification before result-driven iteration.

## Stage 7 — Main Evidence
Produce the primary evidence required by the frozen Claim Type: estimate the primary estimand for causal claims; validate the construct and establish the primary fact for measurement work; test discriminating predictions for viewpoint-guided work; establish the robust primary fact for descriptive work; or estimate the primary spatial/network relation under its corresponding standard. Interpret uncertainty, magnitude, population, validity, and connection to the frozen claim. Diagnose nulls or failures without outcome-shopping.

## Stage 8 — Threat-Mapped Robustness
Every test must name the threat it addresses. Threats depend on the Evidence Architecture and may concern identification, measurement error, construct validity, sample support, spatial dependence, network construction, model dependence, contamination, alternative explanations, or external validity.

## Stage 9 — Mechanism and Rival Explanations
Mechanisms follow the main effect. Prefer tests that distinguish favored channel A from plausible rival B. Avoid mechanical mediation unless causal requirements are credible.

## Stage 10 — Claim Ladder
Classify the strongest supported statement: validated measure/new fact, descriptive fact, association, causal effect, causal mechanism, or external generalization. The ladder is a claim-boundary tool, not a requirement to climb toward causality. A strong descriptive or measurement contribution is valid when its claim matches its evidence.

**Research Director checkpoint:** apply the Stage 6–10 Research Director / Evidence Integrator review.

## Stage 11 — Writing
Build the argument architecture under `protocols/manuscript_argument_integrity.md`. Stabilize evidence-bearing sections, map the Core Question / Claim / Evidence, use lightweight section and paragraph contracts, then run claim-forward prose, anti-defensive-boundary, two-way alignment, and change-impact checks. Rebuild the Introduction, Abstract, and Title from the stabilized evidence system and audit the exact deliverable. Verify citations, avoid invented references, keep claims within evidence, and leave unresolved facts as TODO.

## Stage 12 — Adversarial Review
Use R1 Identification / Validity Specialist, R2 Field Expert, and R3 Generalist/Editor; R3 includes an Argument & Prose Integrity Pass under `protocols/manuscript_argument_integrity.md`. Classify blocking/major/minor comments. Do not recommend submission while blocking comments remain.

**Research Director checkpoint:** apply the Stage 11–12 Internal Editor + SSCI Q2/Q1 Referee review.

## Stop rule
Apply `gates/stop_reopen_rules.md`. Universal STOP/HOLD conditions concern scientific importance, occupied contribution, unjustified geography, invalid or unobservable constructs, inadequate data, claim-architecture mismatch, inability to discriminate serious rivals, unavailable essential data, or disproportionate workload. For causal claims, treatment, assignment, counterfactual, contamination, and attribution failures are additional conditions.

## Reopen rule
Reopen only when new evidence changes a blocking condition.

## Scope-change rule
If Claim Type, Evidence Architecture, key construct, primary evidence, geographic scope, sample population, or central claim changes, explicitly audit the scope change before treating the revised design as the same project. For causal papers this also applies to treatment, estimand, comparison group, identifying assumption, or causal claim.
