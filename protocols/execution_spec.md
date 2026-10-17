# Execution Specification Protocol

Minimum fields: PERW version; stage/gate; objective; Claim Type; Evidence Architecture; research objects (key construct, primary evidence, unit, geography, and causal objects when applicable); inputs; tasks; required outputs; evidence/decision criterion; prohibited actions; escalation conditions.

For nontrivial data-bearing tasks also specify: `DATA_ACCESS_MODE`; expected autonomous sources; potential restricted sources; PI handoff trigger; branch pause condition; resume condition/checkpoint; and work that may continue independently. Default `DATA_ACCESS_MODE` is agent-first acquisition under `protocols/data_access_handoff.md`.

For research-code tasks, apply `protocols/research_code_economy.md` within the existing tasks, outputs, and validation criteria. No separate implementation-mode field is needed. Preserve required scientific checks and verify output/result equivalence after substantive simplification.

For nontrivial research tasks, apply `protocols/research_skill_routing.md`. Default skill routing is `AUTO`; use `PINNED` or `NONE` only when the task requires an explicit choice. Selected skills remain subordinate to PERW, the frozen design, and this execution specification.

For method-intensive claim-bearing tasks, apply `protocols/method_runtime_readiness.md` and identify the readiness artifact and affected-branch decision. Do not add readiness fields to trivial tasks or treat readiness as scientific approval.

## Task completion and verification reuse

Complete the requested work and its necessary consequences within the authorized scope, using the existing tasks, outputs and evidence/decision criteria. Reuse existing evidence while its version, inputs, rules and scope remain applicable. Run the minimum checks required by the acceptance criteria and identified risks; a plan or an easier subset is not task completion.

When an input, rule, dependency or result changes, trace the affected dependencies and revalidate/recompute those uses; expand only when evidence indicates broader impact or an unresolved dependency boundary. Do not add another review pass, hash, report, test suite, file or Agent solely because another pass is possible. Preserve required measurement validation, independent replication, blind review, security checks and all other mandatory safeguards; execution economy never waives them. For measurement changes, use the existing dependency/status rules in [risk-based measurement validation](risk_based_measurement_validation.md).

When the acceptance criteria are met and no in-scope blocker remains, deliver the required report and stop the task. If criteria remain incomplete, report those criteria, unresolved risks and UNKNOWN honestly; do not substitute an unrelated successful check for missing evidence. Task completion does not establish scientific validity, pass a scientific Gate or change scientific Stop / Reopen rules. This rule adds no checklist, mandatory report, implementation-mode field or separate stopping protocol.
