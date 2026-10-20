# Research Skill Routing Protocol

PERW remains the governing workflow. Installed research skills are optional, task-level aids; their absence never blocks PERW execution and their presence never grants research authority.

## When to route

For a nontrivial research task, first identify the current Stage, Claim Type, Evidence Architecture, task objective, and capability actually needed. Inspect the skills that are available in the current runtime or project rather than assuming that a published catalog is installed. Select the smallest set that materially improves the task, and load only the selected skill instructions and directly required references.

Do not load a broad skill collection merely because it is available. A router or index may help locate a specialist skill, but it does not replace scientific judgment or perform the substantive task.

For a nontrivial research decision, ask whether the decision is literature-anchoring material. If yes, check the project's Literature Benchmark Map, locate and verify the relevant source, extract only the generalizable logic, confirm design fit, and then execute under `protocols/high_quality_literature_anchoring.md`. Do not wait for the PI to request a Q1/Q2 paper separately for every material construct or method decision, and do not change a frozen object because a prestigious paper uses another design.

## Authority and conflict order

Resolve instructions in this order:

**PI DECISION > PERW > FROZEN PAPER DESIGN > TASK EXECUTION SPEC > APPROVED EXTERNAL SKILL > TOOL DEFAULTS**

PI decisions use the existing PERW decision, escalation, and workflow-update process; the hierarchy does not authorize an agent to bypass it. An external skill may refine execution or presentation only within the approved task. It may not silently alter the Core Question, Claim Type, Evidence Architecture, key construct, primary evidence, geographic scope, sample population, central claim, Paper Scope, or any protected causal design object.

Classify each material fit decision as:

- **APPLY:** compatible and useful as written;
- **PARTIALLY APPLY:** use only named components and state the boundary;
- **REJECT:** conflicts with PERW, the frozen design, or the task;
- **ESCALATE:** would require a protected design, scope, authority, or workflow change.

Reject any skill that optimizes significance, searches outcomes/specifications/samples for publishable results, suppresses null or unfavorable evidence, treats formatting consistency as scientific verification, upgrades causal language, or substitutes a fixed journal template for Claim Type and Evidence Architecture. A skill catalog's inclusion of a method is not approval to use it.

## Candidate admission decisions and disposition

Each candidate has exactly one admission decision: `INSTALL`, `DISTILL`, `REJECT` or `HOLD`. Keep this decision separate from the evidenced disposition, scientific approval and runtime evidence:

| Admission decision | Intended action | Evidenced disposition |
|---|---|---|
| `INSTALL` | Install or directly integrate the named component within its approved version and scope. | `INSTALLED` only when that implementation exists; not proof of scientific approval or successful execution. |
| `DISTILL` | Retain reviewed, useful method logic in an existing skill or check. | `DISTILLED` only when incorporation is documented, with the retained logic and source; not proof that upstream code was copied or executed. |
| `REJECT` | Decline the affected candidate or integration with a documented reason under the criteria below. | `REJECTED`; functional overlap alone is insufficient. |
| `HOLD` | Suspend the affected use for one of the three reasons below. | `HOLD`, with the specific blocker and unlock condition. |

Only these HOLD reasons are permitted:

- `LICENSE_UNRESOLVED`: the license or permission boundary of the specific component is unresolved.
- `DEPENDENCY_UNAVAILABLE`: a necessary dependency or actual access condition is unavailable.
- `CONFLICT_NO_REPLACEMENT_VALUE`: a direct conflict with an existing capability lacks sufficient justification for replacing that capability.

Record both the blocker and unlock condition for every HOLD. Temporary non-use at the current Stage is not a HOLD reason. Source, security, fit and validation checks remain necessary, but do not create additional HOLD categories; unacceptable risks or scientific conflicts remain subject to rejection under the authority/conflict order.

Admission decisions authorize handling; they do not prove completion. Record an unimplemented action in the existing action/evidence fields without inventing a fifth admission decision or claiming `INSTALLED` or `DISTILLED`. Adaptation is an integration mode, not another admission decision or proof of installation, approval or validation. Use an existing registry's equivalent fields and compatible mappings; do not create a second registry, overwrite historical states, or collapse `scientific_approval`, per-operation/per-host status and execution evidence into disposition. A mapping needs evidence: `APPROVED_COMPONENT` or `APPROVED_GUIDANCE_ONLY` alone does not establish `INSTALLED` or `DISTILLED`.

Keep external existence/discovery, installed software, project implementation, scientific approval, actual function/command execution and validated execution separate. Reading guidance does not prove that its original script ran. Execution on one host or operation does not validate another. Preserve the independent capability states in [method/runtime readiness](method_runtime_readiness.md).

`ADOPTION` does not establish `DISCOVERABLE`: installation or distillation records do not prove that the current host can discover an entry from the active project directory. Record native discovery separately with the observed host and working-directory scope; discovery does not grant admission or execution approval. Derived catalogs, exports and discovery views confer no admission authority and must not replace the existing authoritative registry.

## Proportionate candidate admission

Before admitting or materially changing a selected component, reuse applicable evidence and check:

1. Source identity, pinned version/commit where reproducibility warrants, license/redistribution terms and security boundaries. Unresolved permission to copy or execute is `HOLD / LICENSE_UNRESOLVED`; do not copy or execute material without the required permission.
2. Implementation, dependencies, maintenance and actual host compatibility, including network, credentials and side effects where relevant.
3. Overlap with existing PERW, skills and native functions. Functional overlap alone cannot justify `REJECT`. Where a lawful, feasible and comparable replacement opportunity exists, judge performance on the same bounded task and inputs using predeclared criteria, reusing applicable evidence. Replacement requires no critical error or material regression and a clear advantage in at least one predeclared dimension, including justified maintenance cost. Evidence of insufficient benefit may justify rejecting a new integration; overlap itself does not. Popularity is only a discovery signal, never proof of methodological quality, licensing or reliability.
4. Component class and methodological impact: method knowledge, executable tool or end-to-end workflow; identify whether it affects scientific judgment or protected research objects.
5. Record one of `INSTALL / DISTILL / REJECT / HOLD` and the evidenced action/disposition using the mapping above, with rationale and operation boundaries; do not automatically change any approval. Put method distillation first in existing skills, checks or the unique corresponding capability directory; if a sufficient check already exists, record the source and retained logic without duplicating it. Candidate additions do not justify expanding other central protocols. Retire a replaced step only after the replacement passes acceptance; do not maintain duplicate implementations indefinitely.
6. The smallest validation that demonstrates the intended use: tools require a relevant fixture or actual run with checked outputs; method guidance requires inspectable sources, fit review and a bounded real-task trial; end-to-end workflows contribute only applicable reviewed components. A tool with no scientific decision role needs no invented method-approval gate, but its output cannot authorize a method or replace required data/measurement checks.

Check whether the baseline already incorporates the candidate's distilled logic before interpreting a comparison. Such baseline contamination is not evidence of no incremental value: for an already-distilled component, record `ALREADY_DISTILLED_TEST_CANNOT_RESOLVE`, retain the original outputs and existing distillation, and do not infer rejection from similar outputs. This is a comparison-evidence label, not a new admission disposition or an instruction to rerun tests.

Apply the existing authority/conflict order above throughout. Validation is local to the recorded version, host, operation and task; installation or a smoke test never changes the Core Question, Claim Type, Evidence Architecture, sample population, causal objects, Stage/Gate or scientific authority. No batch installation or automatic active-project migration follows from admission.

## External end-to-end workflows

Treat an external end-to-end research workflow as a **capability collection**, not a second central workflow. Load only the task-relevant component: citation-topology tactics may support literature search; execution/archive conventions may support reproducibility; table, figure, or writing checks may support approved deliverables. Its Stage order, method menu, universal endogeneity phase, mechanism template, heterogeneity battery, significance-improvement loop, journal format, or thesis format never controls a PERW project.

External method menus do not select the causal design, and external default mediation procedures do not determine the mechanism strategy. Do not import a universal Hausman FE/RE rule, automatic TWFE default, `F > 10` valid-IV shortcut, fixed clustering or event-window threshold, or fixed mediation or heterogeneity procedure. PERW Stage structure, frozen design, scientific authority, and conflict hierarchy remain controlling; no project depends on an external end-to-end skill.

## Execution and reporting

Default routing is `AUTO`. Use `PINNED` only when an approved execution specification names a skill, and `NONE` when no available skill adds value. This does not create a new project-level field.

`AUTO` identifies and selects relevant skills; it does not prove that required software exists, that a project implementation runs, or that the method is scientifically valid. Keep these states distinct: **EXTERNAL EXISTS**, **DISCOVERABLE SKILL**, **INSTALLED SOFTWARE**, **PROJECT IMPLEMENTATION**, **SCIENTIFICALLY APPROVED**, and **VALIDATED EXECUTION**. If installation or runtime validation is required, apply `protocols/method_runtime_readiness.md`. `PINNED` may require a named skill only within an approved execution specification; no external skill becomes a PERW dependency.

The execution report includes a compact skill-routing block when routing had a material effect:

- skills inspected or discovered;
- skills selected and why;
- skills rejected or not used and why;
- conflict result: APPLY / PARTIALLY APPLY / REJECT / ESCALATE;
- material effect on procedures, checks, or deliverables.

Report only materially screened skills, not every installed item. If a skill changes no procedure, check, or deliverable, a one-line `SKILL ROUTING: NONE MATERIAL` is sufficient.
