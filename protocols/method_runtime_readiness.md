# Method & Runtime Readiness Protocol

This protocol connects an approved evidence design to a validated empirical implementation:

**scientific job → method fit → data/support fit → temporal/provenance fit → runtime capability → minimal validation run → readiness decision**

It is an execution-readiness protocol, not a numbered Stage, Gate, method-selection score, or econometric cookbook. It does not replace Stage 3 feasibility Gates, the Stage 4 Scope Contract, or the Stage 5 Evidence & Identification Blueprint.

## Trigger and scope

Apply before the first **claim-bearing formal estimation or inference** when the estimator, inference procedure, sensitivity method, fixed-effect structure, control architecture, sample restriction, support requirement, or external runtime dependency is materially nontrivial. Stage 6 measurement or construct-validation work may trigger it; simple Stage 7 descriptive evidence may not.

Routine reruns of a validated, unchanged pipeline do not require a new full audit. Re-audit only the affected branch when a materially new component is introduced.

## Method / component readiness record

For every materially relevant component, record:

- component or method and its **scientific job**: the question, estimand, threat, rival, measurement problem, or inference task it serves;
- fit with the frozen Claim Type and Evidence Architecture;
- **scientific role:** `PRIMARY`, `HIGH-VALUE ROBUSTNESS`, `AUXILIARY / APPENDIX`, or `NOT NEEDED`;
- required data, assumptions, support, temporal provenance, and runtime implementation path;
- actual support as applicable: sample size, positive outcomes/events, clusters/groups, within-unit or within-cell variation, fixed-effect support, and subgroup support;
- capability states, numerical risks, incremental scientific value, and claim boundary;
- **readiness status:** `READY`, `READY_WITH_LIMITATIONS`, `PAUSED_FOR_PI_DATA`, `REJECT`, or `ESCALATE_TO_RESEARCH_DIRECTOR`.

Scientific role and readiness status are separate. A primary method can be unready; an executable auxiliary method can still be `NOT NEEDED`. Statistical significance is never a readiness criterion.

## Capability-state separation

Record these states independently:

1. **EXTERNAL EXISTS:** the public method, skill, package, or implementation exists.
2. **DISCOVERABLE SKILL:** the current runtime can discover and load the skill.
3. **INSTALLED SOFTWARE:** the required library, package, executable, or environment is present.
4. **PROJECT IMPLEMENTATION:** a runnable implementation exists in the project.
5. **SCIENTIFICALLY APPROVED:** the method fits the frozen design and has an approved scientific job.
6. **VALIDATED EXECUTION:** the actual implementation has passed proportionate numerical, reproducibility, and output checks.

**EXTERNAL EXISTS ≠ DISCOVERABLE SKILL ≠ INSTALLED SOFTWARE ≠ PROJECT IMPLEMENTATION ≠ SCIENTIFICALLY APPROVED ≠ VALIDATED EXECUTION.**

An installed skill or package never authorizes a scientific method. Absence of a specialist skill does not block a scientifically necessary method when it can be implemented and independently validated another way.

## Skills, software, and runtime setup

Use `protocols/research_skill_routing.md`. If installation materially improves an approved task, install only the smallest necessary component, prefer an isolated or project-local environment when practical, and pin the version, tag, or commit when reproducibility warrants. Record source, version, Python/R/Stata/system requirements, and whether restart is required. Then verify discovery, importability or executable availability, and the smallest useful example.

Do not install a broad catalog for optionality. GitHub stars, public availability, successful installation, or software capability are not methodological approval and do not replace implementation validation.

## Temporal and event-time provenance

For any covariate, state, or exposure intended to represent pre-event, pre-treatment, or pre-announcement information, distinguish:

- **reference period:** the economic period or state described;
- **information availability date:** when the relevant decision-maker or research unit could have known it, when the design requires an as-of information set;
- **database vintage / extraction date:** when the researcher obtained the value;
- **revision / backfill status:** whether it was later restated, reconstructed, or backfilled.

A latest download is not automatically a contemporaneously known value. A later extraction date is also not automatically invalid. If the construct requires contemporaneously available information, verify the as-of information set. If it requires only a valid historical state, a later vintage may be acceptable when post-event information did not redefine that prior state.

When temporal validity cannot be established, reconstruct the appropriate historical/as-of value, downgrade the variable to descriptive or heterogeneity use, exclude it, or escalate if it is scientifically central. Never silently use a realized or post-treatment variable as a pre-treatment control.

## Sample-composition diagnostic

When a new control block, merged source, or restriction materially changes support, compare where feasible:

A. the broader approved or frozen sample with the relevant base specification;

B. the restricted common-support sample with the same base specification;

C. the same restricted sample with the new controls or architecture.

This diagnostic separates **sample-composition change** from **covariate-adjustment change**. It does not automatically redefine the primary specification, estimand, Claim Type, frozen sample, or main result. Do not present a scientifically invalid no-control model as primary merely because it appears in the diagnostic. Report group-specific support and missingness when comparison groups are affected asymmetrically.

Do not impose a universal attrition threshold. A project may predeclare a justified threshold before estimation.

## Sparse-outcome and saturated-model readiness

Before materially nontrivial nonlinear probability, count, survival/event-history, conditional-likelihood, high-dimensional fixed-effect, or heavily interacted specifications, audit as applicable:

- positive outcomes/events and effective support;
- within-cell, within-unit, and within-cluster variation;
- fixed-effect burden, singleton structure, and subgroup support;
- separation or perfect prediction, estimator existence, and convergence;
- cluster count, covariance stability, and rare influential cells;
- whether the method has distinct incremental scientific value.

**Complexity is not evidence quality. Method sophistication is not contribution.** Reject a numerically fragile or poorly supported method that adds no distinct scientific information.

PERW imposes no universal positive-event minimum, events-per-variable ratio, positive-rate cutoff, cluster-count cutoff, attrition cutoff, fixed-effect-count cutoff, or parameter-to-event ratio. Require method-specific diagnosis, justification, and evidence instead.

## Minimal validation run

Before setting `VALIDATED EXECUTION`, perform the smallest scientifically useful validation proportional to the risk. Depending on the method, this may include software discovery/import, a known-result or package-example check, a simple nested-model comparison, convergence diagnostics, alternative implementation, independent calculation, expected sample/support counts, coefficient/uncertainty consistency, or a justified synthetic-data check. Do not require every validation type mechanically.

## Decision and branch behavior

- `READY`: required scientific, data/support, provenance, runtime, and validation checks pass.
- `READY_WITH_LIMITATIONS`: execution is usable within an explicit claim boundary and recorded limitations.
- `PAUSED_FOR_PI_DATA`: required data are access-blocked; follow `protocols/data_access_handoff.md` and pause only dependent work.
- `REJECT`: the component is unnecessary, unsupported, invalid, or too fragile for its proposed role.
- `ESCALATE_TO_RESEARCH_DIRECTOR`: resolution requires scientific judgment or a protected design decision.

A failure normally blocks only the affected method or component branch. Rejecting optional nonlinear robustness does not stop the project; a failed secondary mechanism leaves that mechanism unresolved. If the failed component is the only scientifically credible implementation of frozen primary evidence, escalate. Do not silently replace the primary method, outcome, treatment, construct, sample, Claim Type, or Evidence Architecture.

Re-readiness is branch-local when an estimator or inference method changes materially; new controls or sources change support or temporal provenance; fixed effects or sample architecture change materially; a runtime upgrade affects the authoritative implementation; numerical failure requires another estimator; or a skill/software version changes in a scientifically material way.

## Scientific boundary

Method & Runtime Readiness improves execution credibility. It does not establish causal identification, authorize a method because it exists, permit scope change or result-driven search, authorize outcome/sample switching, or override Research Director and PI authority. Preserve **Paper Scope ≤ Identified Claim ≤ Evidence**, no significance hunting, no complexity rescue, reproducibility, and all frozen-object rules.
