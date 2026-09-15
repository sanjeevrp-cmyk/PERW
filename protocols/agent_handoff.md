# Agent Handoff Protocol

ChatGPT should issue an EXECUTION_SPEC for consequential execution tasks. The executor returns an EXECUTION_REPORT. Handoffs should separate research judgment from empirical execution without creating bureaucracy. An executor does not gain permission to alter research design merely because an implementation problem appears.

Required loop:

**ChatGPT → EXECUTION_SPEC → Codex/Hermes → EXECUTION_REPORT → ChatGPT scientific review → PI decision**

For data-bearing tasks, insert the following sub-loop only when needed:

**Codex/Hermes autonomous acquisition → if accessible, execute → if restricted, PI_DATA_REQUEST + PAUSED_FOR_PI_DATA → PI data delivery → DELIVERED_PENDING_VALIDATION → executor validation/resume → EXECUTION_REPORT**

Follow `protocols/data_access_handoff.md`. Unrestricted tasks do not require extra handoff steps. A restricted-access pause is operational, not a scientific Gate decision.

Execution success does not establish scientific validity. ChatGPT must review the returned evidence, assumptions, deviations, failures, and claim implications before recommending a research decision. Codex/Hermes may flag problems and propose alternatives, but major research-design changes require explicit scientific review and PI approval.
