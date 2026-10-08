# Risk-Based Measurement Validation

Make high-risk scientific-object construction credible before scaling it, and allocate independent checking to the errors that could matter. This protocol operationalizes existing measurement-validity, provenance, independent-verification, and escalation requirements. It adds no Stage, Gate, passing criterion, scope-freeze authority, causal standard, or Stop / Reopen rule. Agent agreement, model confidence, and reproducible code do not establish scientific validity.

## A. Pre-production measurement stress test

**Trigger:** core evidence depends on complex manual coding, historical state reconstruction, event boundaries, entity relationships, or multi-source matching whose rules or scalability are not yet credibly validated. Apply a bounded test before expensive production or materially scaling a revised construction. Ordinary validated imports and unchanged, still-applicable rules do not automatically need another full test.

At Stage 1–2, use `protocols/early_data_feasibility.md` for the cheapest informative version; at Stage 6, validate the actual production rules and pipeline before scaling. Reuse valid early evidence when its sources, rules, coverage, and implementation still apply. This is neither a second Data / Measurement Gate nor an automatic return to earlier stages.

1. State the scientific object, observational/event unit, time/state interpretation, inclusion/exclusion boundaries, key construct, and primary evidence under the approved specification. Distinguish source documents, mentions, entities, events, and analysis observations; one document or matching ID need not represent one scientific event.
2. Assemble a small, high-information challenge set covering typical, boundary, anomalous, and expected error-prone cases. Include plausible negatives, exclusions, ambiguous matches, repeated or split events, and historical changes where relevant. Deliberate stress cases test failure modes; do not present them as a representative sample or a population error-rate estimate.
3. For each case retain source/version and location, the rule/version, the construction or judgment, its evidence and rationale, unresolved alternatives, and a reproducible record identifier. Use verified known-answer or benchmark cases when available; document how the reference answer was established independently of the production output. Synthetic known-answer tests validate implementation logic, not real-world construct validity. A majority label or an unverified benchmark is not ground truth.
4. Test both rule meaning and implementation: units and boundaries, historical/as-of consistency, joins and duplicates, observable versus missing states, sample inclusion, and source-to-record traceability. A pipeline that runs without error may still construct the wrong object. Where uncertainty is real, preserve UNKNOWN or the competing interpretations rather than force a label for completion.
5. Before scaling, record observed failures, repairs and retests, residual ambiguity, coverage limits, and whether the core rules are credibly scalable under existing validity standards. Explain why the evidence is sufficient for the proposed scale and scientific job, or what remains unresolved. Do not claim readiness from agent agreement or data-engineering convenience.

There is no universal stress-test sample count, agreement percentage, or quality-score cutoff. Coverage and review intensity follow scientific risk and the consequences of error; any task-specific criterion must be justified in advance. Unresolved material threats use existing Gate, affected-work pause, and escalation rules rather than a new approval system.

## B. Risk-based independent audit

Keep the purpose, information available, coverage, and limitations of each mode explicit:

| Mode | Scientific job and boundary |
|---|---|
| Independent Replication | Independently implement the specified construction or analysis from identified inputs and rules; compare relevant counts, provenance, measures, samples, results, uncertainty, and validity checks under `protocols/independent_replication.md`. Withhold target outputs when practical. This can reveal implementation dependence but does not by itself prove the underlying rule is scientifically correct. |
| Blind Independent Spot Check | Independently judge a preselected subset from source evidence and approved rules before seeing the primary labels, rationale, or target results; lock the independent answers before comparison. Estimate only what the sampling design supports. A spot check is not full independent replication. |
| Non-blind Adversarial Audit | Examine known constructions, rationale, suspicious cases, or disagreements to challenge weak rules, omitted evidence, and alternative interpretations. Useful for diagnosis and targeted repair; it does not substitute for necessary blind checking or measure unbiased agreement. |
| Evidence Adjudication | Reconcile a material disagreement against source evidence, dates, object definitions, and approved rules; preserve competing judgments and reasons. It is not majority voting, agent seniority, or authority to redesign. |

**Asymmetric work is allowed:** the primary executor may construct the full dataset while an independent auditor concentrates on high-risk objects, major disagreements, and a proportionate, predeclared stratified random blind spot check. Select the combination for its scientific job; neither every paper nor every record requires mechanical double coding. Preserve necessary blind review whenever shared assumptions, anchoring, subjective rules, or undetected common errors threaten core evidence. Do not replace an independently specified necessary replication task with a spot check merely to save effort.

### Blind sampling and common-error discovery

- Predeclare the audit frame, risk strata, random selection method/seed, coverage rationale, blinding scope, and any error-driven expansion logic before inspecting agreement or empirical results. Freeze the selected IDs and relevant source/rule versions; do not replace difficult cases or redraw a favorable sample. An already inspected case cannot be relabeled blind; record contamination and obtain a fresh unexposed sample when necessary.
- Give the blind reviewer the sources and approved definitions needed to judge the object, but withhold primary labels, primary rationale, and target outputs until independent judgments are recorded. A separate non-blind investigation can follow. Record what was actually withheld and any independence limits; a different agent name alone does not establish independence.
- Sample beyond flagged disagreements: cover ordinary and apparently agreed cases as well as high-risk strata. Check the raw/source candidate universe and excluded, unmatched, rejected, or unconstructed cases as relevant, not only surviving records. Source-to-record checks reveal missed objects and false exclusions; record-to-source checks reveal invented, duplicated, or misclassified objects. Review shared rule and evidence failures even where both executors agree.
- Keep targeted and randomly drawn findings separate. Do not infer a population error rate from a risk-selected subset or extrapolate an unweighted stratified rate to the whole dataset. If broader accuracy is needed, use a justified sampling design and report its support and uncertainty. No universal blind-review fraction or agreement threshold is imposed.

Agreement by two agents does not prove a fact; disagreement does not prove that the primary executor is wrong. Apparent Codex competence, Hermes independence, software output, or a label-error detector cannot make a judgment true. Model flags are review leads, not automatic relabeling, exclusion, or scientific decisions.

### Evidence adjudication and authority

For each material disagreement, link the record/source and rule version, competing judgments, relevant original evidence and its temporal validity, the reason for resolution or continued uncertainty, the affected dependencies, and the responsible existing decision-maker. Apply approved mechanical rules to correct demonstrated execution errors; investigate whether a discrepancy is an implementation error, ambiguous evidence, or an inadequate scientific definition.

Codex/Hermes may report and repair factual implementation errors within approved rules and propose alternatives. Research Director review and PI decision remain required for protected object or scope changes under `protocols/escalation_protocol.md` and `protocols/research_genesis_branch_governance.md`. No executor receives new scientific adjudication authority. If evidence cannot resolve a material issue, record UNKNOWN / PENDING and the implication; do not settle it by rank or forced consensus. The existing rule remains: **Material disagreement stops interpretation until reconciled.** Record why the resolution supports the claim, or route an unresolved validity threat through existing rules.

## C. Change-impact and selective revalidation

When a key measurement or construction rule changes, trace its actual dependencies:

An impact assessment does not authorize a change to a frozen object. Obtain any required existing scientific review and PI decision before implementing a protected change; approved implementation repairs retain their existing execution route.

**raw evidence → constructed records → sample membership → key constructs → authoritative datasets → estimated results → exhibits → manuscript claims**

Record old/new rule and input versions, the reason for change, affected IDs or partitions, shared transformations and downstream uses, the evidence for each impact classification, and the validation/recomputation needed. Store this in existing execution reports, provenance or result registries; link rather than duplicate them. Preserve superseded artifacts as historical outputs with their version and status, never silently as current evidence.

| Artifact status | Required basis and handling |
|---|---|
| VERIFIED REUSABLE | Evidence establishes that the artifact is unaffected or remains valid/equivalent under the current rule, population, and claim. Record the basis; existence, an unchanged filename, or matching aggregate counts alone is insufficient. |
| REVALIDATION REQUIRED | Relevance or validity may have changed; perform the named check before the artifact supports a current claim. |
| RECOMPUTE REQUIRED | Changed records, sample, construct, or dependent inputs require rebuilding the relevant data or rerunning downstream analysis and outputs. |
| INVALID FOR CURRENT CLAIM | The artifact cannot support the current object/claim; retain only as labeled history or another explicitly justified use. |
| UNKNOWN / PENDING | Impact or evidence is unresolved. Trace further and withhold dependent claims until resolved; do not presume reuse. |

**Core event-unit or state changes:** dependent formal results must be recomputed or explicitly revalidated against the corrected construction. Compare the relevant record identities, sample membership, construct values, model inputs/specifications, estimates, uncertainty, and outputs as needed; numerical similarity alone does not establish equivalence of scientific meaning. If the changed unit/state alters dependent analytic inputs or equivalence cannot be established, recompute. Cost, significance, unchanged headline direction, or prior effort does not justify keeping old numbers.

Contain rework using demonstrated dependencies. Retest the affected rule and cases, inspect the affected stratum and shared transformations, expand when evidence indicates broader/common failure, and rerun the downstream artifacts that depend on changed inputs. Reuse independently unaffected artifacts with a documented basis; a local error does not automatically restart the whole project. Conversely, an unknown dependency boundary is not proof of locality: trace it and keep the unresolved uses pending. Follow `protocols/research_code_economy.md` for proportional implementation and output-equivalence checks.

After repair, verify authoritative datasets/results before updating exhibits and manuscript claims under `protocols/econ_management_publication_architecture.md`; reconcile every affected use, including headline numbers. Unverified, stale, invalid, or pending results cannot continue to support current scientific claims. Validity standards do not fall because construction is expensive, and repairs must not become significance hunting or silent changes to frozen objects.

## Lean records, reuse, and source boundary

Within existing Execution Spec/Report, validation log, Scope Contract, and provenance structures, record only what applies: trigger and scientific object; test-case/source/rule references; audit mode, coverage and blinding plan; findings and adjudication; change/dependency/status map; repair and verification references; unresolved threats and existing escalation decision. No separate event-audit platform, universal double-agent workflow, new mandatory template, software package, or external skill is required. Do not repeat still-valid checks without a material change or new risk. Central release does not migrate active papers; any adoption affecting an active design follows `protocols/workflow_update_governance.md` separately.

Selective sources verified on 2026-10-08 informed general execution principles, not new scientific standards:

- [K-Dense scientific-critical-thinking, pinned revision](https://github.com/K-Dense-AI/scientific-agent-skills/blob/92ace75ac21efe19a620434e0ca4e356081fe807/skills/scientific-critical-thinking/SKILL.md): object/unit definition and source-based critique; clinical grading frameworks are not general PERW requirements.
- [Auto-Empirical-Research-Skills data-validate, pinned revision](https://github.com/brycewang-stanford/Auto-Empirical-Research-Skills/blob/9fa87d86e34d6c9a1c7cdb0db755c83c780537a0/skills/61-phdemotions-research-methods/skills/data-validate/SKILL.md): inspectable validation/source records. This is a collection of attributed upstream skills, not independent confirmation of every method; its fixed multi-agent audit loops and tool stack are not adopted.
- [HumanSignal review](https://docs.humansignal.com/guide/quality) and [benchmark annotations](https://docs.humansignal.com/guide/ground_truths): targeted/random review and separately verified references. Some features are Enterprise-only; neither the software nor its designation of a reference label establishes scientific truth.
- [cleanlab noisy-label workflow](https://docs.cleanlab.ai/stable/tutorials/indepth_overview.html): model-based label-issue discovery can direct review, but flags can reflect ambiguity and require evidence; no model score becomes a PERW criterion.
- [OpenRefine operation reuse](https://openrefine.org/docs/manual/running#reusing-operations): traceable transformations aid impact analysis; some edits cannot be exported as replayable operations and need explicit recording.
