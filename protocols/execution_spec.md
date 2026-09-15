# Execution Specification Protocol

Minimum fields: PERW version; stage/gate; objective; Claim Type; Evidence Architecture; research objects (key construct, primary evidence, unit, geography, and causal objects when applicable); inputs; tasks; required outputs; evidence/decision criterion; prohibited actions; escalation conditions.

For nontrivial data-bearing tasks also specify: `DATA_ACCESS_MODE`; expected autonomous sources; potential restricted sources; PI handoff trigger; branch pause condition; resume condition/checkpoint; and work that may continue independently. Default `DATA_ACCESS_MODE` is agent-first acquisition under `protocols/data_access_handoff.md`.
