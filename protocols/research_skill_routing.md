# Research Skill Routing Protocol

PERW remains the governing workflow. Installed research skills are optional, task-level aids; their absence never blocks PERW execution and their presence never grants research authority.

## When to route

For a nontrivial research task, first identify the current Stage, Claim Type, Evidence Architecture, task objective, and capability actually needed. Inspect the skills that are available in the current runtime or project rather than assuming that a published catalog is installed. Select the smallest set that materially improves the task, and load only the selected skill instructions and directly required references.

Do not load a broad skill collection merely because it is available. A router or index may help locate a specialist skill, but it does not replace scientific judgment or perform the substantive task.

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
