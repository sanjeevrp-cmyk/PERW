# Execution Specification Protocol

Minimum fields: PERW version; stage/gate; objective; Claim Type; Evidence Architecture; research objects (key construct, primary evidence, unit, geography, and causal objects when applicable); inputs; tasks; required outputs; evidence/decision criterion; prohibited actions; escalation conditions.

For nontrivial data-bearing tasks also specify: `DATA_ACCESS_MODE`; expected autonomous sources; potential restricted sources; PI handoff trigger; branch pause condition; resume condition/checkpoint; and work that may continue independently. Default `DATA_ACCESS_MODE` is agent-first acquisition under `protocols/data_access_handoff.md`.

For research-code tasks, apply `protocols/research_code_economy.md` within the existing tasks, outputs, and validation criteria. No separate implementation-mode field is needed. Preserve required scientific checks and verify output/result equivalence after substantive simplification.
