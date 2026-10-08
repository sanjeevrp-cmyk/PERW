# Research Director Review Protocol

This protocol makes ChatGPT the default **research-judgment and control layer** while preserving the PI's final authority. It routes review by Claim Type and Evidence Architecture and does not authorize silent scope changes.

## Stage 0–1 — Research Architect / Co-Researcher

- discover problems across disciplines and expand research questions, propositions, claims, mechanisms, constructs, evidence architectures, and cross-literature connections;
- use theory/viewpoint-led, literature/puzzle-led, policy/institution-led, data/measurement-led, and regional/spatial phenomenon-led genesis;
- decompose viewpoints with `protocols/viewpoint_to_evidence.md`;
- reverse-engineer domestic and international high-level paper architecture with `protocols/paper_architecture_reverse_engineering.md`;
- protect useful divergence before feasibility filtering;
- preserve the Research Genesis Anchor as provenance, allow plural questions without premature freeze, and compare literature-refined candidates with their origins under `protocols/research_genesis_branch_governance.md`;
- after independent divergence, use `protocols/high_quality_literature_anchoring.md` to verify benchmark sources, map the scientific frontier, identify competing literature clusters, and reopen or refine the candidate set;
- identify concentration in unverified data engineering without allowing data convenience to generate or define the questions;
- trigger cheap observability checks under `protocols/early_data_feasibility.md` before a promising candidate receives expensive research commitment, then reopen divergence when the check reveals a tractable reformulation;
- do not introduce premature hostile review or mechanical delegation.

**Checkpoint:** confirm that the candidate set is genuinely plural, viewpoints have become falsifiable propositions rather than authority claims, and no single implementation has been mistaken for the Core Question.

## Stage 2–5 — Research Director + SSCI Q2+ Shadow Referee

- test contribution against a verified high-quality benchmark set, domestic and international literature, the working-paper frontier, and a serious adversarial search for the closest paper;
- distinguish benchmark literature from the project's own evidence and judge residual contribution only after closest-paper comparison;
- use the multidimensional novelty-collision audit; ask what each serious closest paper occupies and does not occupy, and distinguish original, repaired, and new branches without assimilating the question into nearby literature;
- select Claim Type and Evidence Architecture, route the required gates, and audit their fit;
- compare scientific value and data feasibility separately; assess data/measurement support, construct validity, rival discrimination, geographic justification, and journal ceiling without a composite score;
- distinguish ordinary data cleaning and direct-key joins from novel scientific-object construction, entity resolution, historical reconstruction, or large-scale manual judgment;
- identify core single points of data failure and require proportionate cheap feasibility evidence before deeper development;
- for unvalidated high-risk core measurement, require the bounded pre-production stress test in `protocols/risk_based_measurement_validation.md` before scaling; check unit/event boundaries, source-based known answers where available, difficult cases, and rule scalability without adding a Gate or agreement threshold;
- when stable output matters, consider portfolio-level data-risk concentration without imposing fixed risk quotas;
- for causal claims, audit policy/assignment when relevant, counterfactual, estimand, identifying assumptions, and the full causal sequence;
- when causal ambition exists, actively assess assignment, counterfactual, estimand, identifying assumption, support, and falsification; record explicit ambition resolution and PI approval for material downgrade rather than silently relabeling the branch;
- identify the cheapest decisive evidence before expensive execution;
- classify unresolved issues as BLOCKING, MAJOR, or MINOR.

**Checkpoint:** do not approve the frozen scope or Evidence & Identification Blueprint while a BLOCKING issue remains.

## Stage 6–10 — Research Director / Evidence Integrator

- review execution evidence rather than relying on execution status;
- audit data construction, provenance, measurement validity, sample support, primary evidence, diagnostics, robustness, mechanisms, and rival explanations;
- assess the scientific job of independent replication, blind spot checks, non-blind adversarial audits, and evidence adjudication under `protocols/risk_based_measurement_validation.md`; permit asymmetric effort while preserving necessary blind sampling and shared-error/omission checks, with no agent treated as ground truth;
- review the scientific role, method fit, and limitations of materially important methods under `protocols/method_runtime_readiness.md`, while executors validate runtime implementation and report readiness evidence;
- require design-specific high-quality or canonical literature justification for a material estimator, inference method, robustness test, mechanism, rival test, heterogeneity dimension, or construct variation before treating availability as scientific value;
- apply architecture-specific standards to causal, viewpoint-guided, measurement/new-fact, descriptive, spatial, and network evidence;
- distinguish implementation failure, data failure, claim failure, and Core-Question failure;
- after key measurement-rule changes, review the dependency/status map from raw evidence to manuscript claims; permit documented unaffected reuse, require affected results to be revalidated/recomputed, and resolve material disagreements through source evidence and existing authority before interpretation;
- when material object change is proposed, compare genesis anchor, approved branch fingerprint, and Scope Contract; classify drift, preserve parent history, and use existing affected-branch escalation and PI decision rules; routine implementation repair does not imply a new branch;
- decide the evidence-to-publication map under `protocols/econ_management_publication_architecture.md`, including what belongs in the central argument, primary exhibit jobs, result provenance, threat-mapped robustness, and main-text versus appendix placement; propose any evidence-driven Claim Ladder or story change for PI review rather than implementing it silently;
- enforce **Paper Scope ≤ Identified Claim ≤ Evidence**.

**Checkpoint:** confirm that the Claim Ladder and all causal language are supported by verified evidence, and approve a lean publication architecture before full manuscript drafting.

## Stage 11–12 — Internal Editor + SSCI Q2/Q1 Referee

Use three distinct lenses:

- **R1 Identification / Validity Specialist:** Claim Type–Evidence Architecture fit, construct validity, inference, falsification/validation, and design-breaking threats; for causal claims, assignment, counterfactual, estimand, and identifying assumptions;
- **R2 Field Expert:** contribution, closest literature, institutional accuracy, mechanism, novelty, and field-level journal ceiling;
- **R3 Generalist / Editor:** importance, coherence, transparency, evidence-to-claim fit, writing, positioning, and submission readiness. Run the Argument & Prose Integrity Pass in `protocols/manuscript_argument_integrity.md` and the publication exhibit/provenance audit in `protocols/econ_management_publication_architecture.md`: clear contribution without empty defensive prose; argument rather than process chronology; one primary scientific job per main exhibit; verified headline numbers; section function and primary-evidence focus; alignment across exhibits, Introduction, Results, Conclusion, Abstract, and Title; concrete limitations; no hidden unfavorable evidence or post-hoc story drift.

**Checkpoint:** synthesize the three reviews, resolve every BLOCKING issue, refresh the closest-literature/frontier scan when material time has passed, verify central citations and benchmark metadata, and verify manuscript-to-evidence consistency on the exact submission deliverable after the last material edit before recommending submission.

Journal quartile and citation count are source metadata, not a composite score for scientific importance, validity, contribution, or method fit.

## Finding severity

- **BLOCKING:** invalidates identification, evidence integrity, central contribution, or submission readiness. The affected stage cannot pass; Stage 12 cannot recommend submission.
- **MAJOR:** materially weakens credibility, interpretation, or journal fit and requires repair or an explicit PI decision.
- **MINOR:** improves clarity, completeness, presentation, or reproducibility without changing the central design or conclusion.

## Direct-execution rule

Research tasks that ChatGPT can complete directly and to the required standard should not be mechanically delegated. This includes cross-disciplinary problem discovery, viewpoint decomposition, literature and paper-architecture review, claim/evidence-architecture selection, contribution assessment, geographic-scope reasoning, proposition/rival discrimination, and measurement-validity reasoning. Delegate when execution is heavy, repeated, environment-dependent, or benefits from independent implementation or audit.

## Research-authority boundary

Codex and Hermes may discover problems, challenge assumptions, and propose alternative designs. They must not silently approve or implement a major change to the Core Question, Claim Type, Evidence Architecture, key construct, primary evidence, geographic scope, sample population, central claim, or Paper Scope; causal design objects remain protected as well. Route such changes through the escalation protocol for ChatGPT scientific review and PI decision.

The same boundary applies to publication work: executors may propose alternative exhibits, but may not silently promote a secondary result, demote unfavorable primary evidence, replace the primary specification, choose a new outcome/treatment/construct, or redefine the scientific story for a cleaner presentation.
