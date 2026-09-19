# PERW Research Principles

## 1. Scientific value over topic preservation
Do not keep a topic alive because time has already been invested.

## 2. Diverge before converging
At the birth of a research idea, do not immediately collapse the project to the first feasible specification. Generate alternative questions, propositions, mechanisms, claims, and evidence architectures before applying kill tests.

## 3. Question before design family
Do not force every research question into a causal-policy design. First determine the scientific question, intended claim, and required evidence; then choose the empirical architecture.

## 4. Claim-design fit
The evidence architecture must match the intended claim. Do not demand causal identification for a descriptive or measurement claim, and do not use descriptive evidence to support a causal claim.

## 5. Causal identification before estimator
When a paper makes a causal claim, reason in this mandatory order:
**assignment → counterfactual → estimand → identifying assumption → estimator → inference → diagnostics → falsification**
Never begin from “use DID / DDD / IV / DML” and retrofit the research question.

## 6. Evidence boundary
**Paper Scope ≤ Identified Claim ≤ Evidence**

## 7. Separate the question from the implementation
Maintain Core Question, Claim Type, Identified Claim, Evidence Architecture, and Paper Scope as distinct objects. A failed data source or implementation can kill an Identified Claim without killing the Core Question.

## 8. Viewpoint is a hypothesis, not truth
A scholar's, adviser's, policymaker's, or theoretical viewpoint is an input to question generation. Convert it into **viewpoint → mechanism → falsifiable proposition → observable prediction → rival explanation → required evidence**. Test the proposition; do not search for data merely to confirm its source.

## 9. Geographic narrowing is not contribution
Moving from a broad geography to a narrower one is not itself novelty. The narrower setting must add scientific value through identification, measurement, mechanism, institutional variation, spatial interaction, data quality, external relevance, or another defensible reason.

## 10. Architecture borrowing is not contribution
High-level papers may be reverse-engineered for question architecture, construct design, empirical logic, measurement, identification, mechanism, and exposition. Reproducing the same design with only a different geography, year, sample, or outcome is not automatically a contribution.

## 11. Cheap information before expensive work
Do not spend expensive research effort before cheap evidence shows that the evidence required by a scientifically worthwhile question is sufficiently observable and implementable. Before deep literature, design, or data-engineering commitment, distinguish required, observable, and missing evidence and use minimum viable checks such as schema inspection, small representative audits, pilot extraction, support counts, identifier checks, construct checks, policy timing checks when relevant, and competition searches. Data ease does not determine which questions are scientifically valuable; it determines how much further effort is justified before feasibility is verified. Follow `protocols/early_data_feasibility.md` for Stage 1–2 candidates.

## 12. Threat-mapped robustness
Every robustness test must correspond to a named threat. Do not pad the paper with generic robustness tables.

## 13. No significance hunting
Do not switch outcomes, samples, treatments, or heterogeneity dimensions merely to obtain significance.

## 14. No complexity rescue
PSM, DML, machine learning, mediation, fixed-effect proliferation, spatial or network complexity, or arbitrary IVs do not repair a weak design, invalid measurement, claim-evidence mismatch, or weak assignment mechanism.

## 15. Reproducibility is part of research quality
Data construction, variable definitions, sample funnels, seeds, specifications, and output generation should be auditable.

## 16. Independent verification for high-stakes results
Key empirical findings should receive an independent implementation or audit when practical.

## 17. Critical collaboration
Agents should challenge false premises, logical jumps, missing information, and structural risks rather than agreeing for convenience.

## 18. Access failure is not data unavailability
Executors should autonomously obtain data they can legally access. An executor's access limitation does not establish that the PI or research team cannot obtain the data, that the measure has failed, or that the design is invalid. Restricted access pauses the dependent branch and triggers a precise PI data request; only team-level legal unavailability or genuine unobservability may support a data-unavailability Gate decision.

## 19. No implementation bloat
Research code should use the simplest implementation that preserves scientific correctness, auditability, reproducibility, validation, provenance, and rerunability. Simplicity does not mean the fewest lines of code. Do not add abstractions, dependencies, files, wrappers, configuration layers, or duplicated transformations without a current research need. Follow `protocols/research_code_economy.md`; this implementation principle does not relax the separate no-complexity-rescue rule for research design.
