# Research Code Economy

Use the simplest implementation that preserves scientific correctness, auditability, reproducibility, validation, provenance, and rerunability. Simplicity is not the fewest lines of code. PERW scientific requirements override code minimization. This protocol concerns implementation, not research-design complexity or frozen scientific objects.

## Before adding code

Ask in order: Is it needed for the current research task? Does existing code already do it? Do the language's standard capabilities suffice? Does an existing project dependency suffice? Can a smaller, more transparent implementation do it? Do not build for hypothetical future needs. Reuse an existing function, then standard or established capabilities, then a small local helper; add a new layer, class, factory, manager, framework, or generic configuration system only for a demonstrated current need.

## Keep scientific work visible

Do not remove or hide sample funnels, merge and unmatched-ID diagnostics, duplicate and missingness audits, treatment and variable-construction checks, construct validation, data-quality checks, provenance and data lineage, primary diagnostics, required robustness, seeds, inference settings, frozen specifications, audit outputs, reproducibility tests, explicit validation and error checks, or needed checkpoint and resume state. Transparent transformations and sample accounting may require more code; they are scientific observability, not engineering redundancy.

Construct each key variable or sample rule in one authoritative place, including treatment, outcome, winsorization, sample filters, industry mapping, event dates, and entity matching. Other scripts call that construction or read its output; they do not silently copy its logic.

When an old path has been formally replaced and serves no replication, audit, comparison, or rollback purpose, remove it from the active pipeline. Keep necessary history in version control rather than commented-out code.

## After implementation

For nontrivial code tasks, review dead code, duplicate logic or transformations, unused imports and dependencies, unnecessary abstractions or wrappers, needless file splitting or configuration, speculative code, and obsolete branches. An approved code-economy skill such as Ponytail may assist when available; it is optional and cannot override PERW scientific requirements.

After any substantive simplification, perform an output/result equivalence check: compare before and after row and sample counts, variable definitions, primary data outputs, model specifications, estimates and standard errors where applicable, inference settings, seeds, key diagnostics, tables and figures, and file schemas within justified numerical tolerances. If research results change, stop ordinary simplification and investigate the difference.
