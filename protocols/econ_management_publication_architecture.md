# Empirical Publication Architecture Protocol

This protocol bridges **verified evidence → publication exhibits → results narrative → manuscript claims** for empirical economics, management, finance, international business, and related social-science research. It applies mainly across Stages 7–11 and adds a publication checkpoint between the Stage 10 Claim Ladder and full Stage 11 drafting. It does not add a Stage or Gate and does not change Claim Type, Evidence Architecture, causal standards, frozen objects, or agent authority.

## Four output layers

Keep four layers distinct and linked:

1. **Internal diagnostic:** debug plots, merge audits, support histograms, intermediate estimates, regression dumps, validation logs, and failed or null checks needed for scientific judgment.
2. **Main-text exhibits:** the smallest set of tables and figures required to establish the paper's central evidence and inference boundary.
3. **Appendix or supplement:** secondary detail, extended diagnostics, auxiliary robustness, alternative constructions, and material needed for audit without displacing the main argument.
4. **Replication artifacts:** authoritative code, data lineage, machine-readable results, logs, and environment information needed to reproduce reported outputs.

Placement is determined by scientific function and importance to the central claim, not by whether an output is visually attractive or already available. Null, unfavorable, or design-threatening evidence may not be hidden through placement.

## Publication architecture

Before full drafting, maintain a lean publication architecture using `templates/PUBLICATION_ARCHITECTURE.md`. For every proposed exhibit, record its primary scientific job, the claim it supports, its authoritative result source, its intended layer, and the threat or rival it addresses when applicable. Mark irrelevant conditional fields `N/A`; do not create empty paperwork.

Each main exhibit has **one primary scientific job**. It may contain multiple panels or models only when they jointly perform that job. If an exhibit tries to establish the main result, robustness, mechanism, heterogeneity, and context at once, split it or demote secondary material.

There is no universal number, sequence, or journal-house format for tables and figures. Architecture follows Claim Type, Evidence Architecture, field conventions, and the target journal's current instructions. Adaptation should use a small verified set of relevant exemplars plus current author guidance; an external template is evidence about presentation, not authority over the research design.

## Table standards

Regression and estimation tables should be interpretable without reverse-engineering. As applicable, show or state:

- outcome, focal estimate or contrast, units, scale, and reference category;
- model/specification differences and the reason each column is present;
- uncertainty measure and inference method, including clustering or dependence treatment;
- estimation sample and observation or cluster counts;
- fixed effects, controls, weights, transformations, and missing-data treatment when material;
- estimand or target quantity for causal work, and the corresponding non-causal target for other architectures;
- scientifically meaningful model diagnostics such as fit measures or first-stage statistics;
- intuitive labels and consistent numeric precision;
- notes that define symbols, tests, panels, and deviations from the main specification.

Do not paste raw software output or CSV matrices into a manuscript. Do not report precision as importance. Interpret statistical precision, magnitude, and causal meaning separately. A magnitude statement must use an observed or explicitly derived scale, denominator, baseline, or benchmark; never invent one to make an estimate sound meaningful.

## Figure standards

Every figure must perform a scientific function such as defining a construct, showing support or overlap, displaying dynamics, communicating uncertainty, testing sensitivity, discriminating rivals, or interpreting magnitude. Use informative axes, units, reference lines, sample/method notes, readable labels at final size, and accessible color/shape choices. A decorative chart or a duplicate of a table without a distinct reader function does not qualify as a main exhibit.

## Ordering and threat mapping

Exhibit order follows the paper's scientific logic, conditional on Claim Type and Evidence Architecture. A typical order may move from measurement or design validity to primary evidence, magnitude, threat-mapped robustness, mechanisms/rivals, and bounded heterogeneity, but this is not a mandatory causal sequence.

Every robustness exhibit must identify:

1. the threat;
2. why it matters and why the test is informative;
3. what result would alter the claim;
4. the observed result and its authoritative source;
5. the consequence for the claim;
6. any remaining uncertainty.

A generic battery of alternative specifications does not become publication evidence merely because estimates remain significant.

## Provenance and verification order

Maintain a traceable chain:

**raw/derived data → authoritative code → machine-readable result → result registry → table/figure → manuscript sentence**

Each reported number has one authoritative source. Headline numbers require a compact register containing source, transformation, exhibit location, manuscript uses, and last verified run. After a rerun or substantive change, reconcile every affected exhibit and sentence; do not hand-copy a stale value.

Verification occurs in this order:

1. **Verify Results:** confirm that authoritative code and inputs reproduce the reported quantity within a declared tolerance, with sample, units, specification, and uncertainty intact. Label missing, mismatched, or unreproduced quantities as unverified.
2. **Verify Claims:** confirm that each sentence is supported by a verified result, exhibit, or citation at the stated population, scope, direction, magnitude, and causal level. Narrow, qualify, or remove unsupported claims; never repair them by inventing evidence.

Formatting consistency is not result verification. Claim verification cannot pass when its underlying result is unverified.

## Roles and approval

The Research Director decides, within the approved scientific scope, which evidence belongs in the central argument, which exhibits belong in the main text or appendix, and whether new evidence warrants a proposed Claim Ladder or story change; the PI retains final authority. Executors may propose alternatives and build, trace, and validate exhibits under the approved specification. They may not silently promote a secondary result, demote unfavorable primary evidence, replace the primary specification, choose a new outcome/treatment/construct, or move the paper to a new story. Any resulting change to the paper's central claim, scope, interpretation, or protected object requires the existing escalation and scope-change process. Publication architecture organizes approved evidence; it does not redesign the study.

## Publication deliverables

As required by the project, executors should be able to produce publication-ready tables and figures, self-contained notes, appendix exhibits, a result-provenance register, an exhibit-claim map, reproducible generation scripts, a machine-readable result registry, and a consistency report. Formats follow the project's canonical toolchain: LaTeX, DOCX, spreadsheets, HTML, or another approved format may be used. No format is universally required.

When an installed skill would materially improve econometric implementation, evidence binding, result or claim verification, visualization, scientific writing, or code economy, route it through `protocols/research_skill_routing.md` and use only the smallest compatible set.
