# Workflow Update Governance

PERW supports controlled continuous improvement. A new GitHub skill, paper, referee comment, or project experience is a candidate input, not an automatic rule.

## 1. Candidate update sources

Candidates may come from:

- high-quality GitHub research skills or workflows;
- new econometric methods or best practices;
- SSCI, economics, or finance journal-review experience;
- successful or failed paper-project experience;
- workflow defects identified by ChatGPT, Codex, or Hermes;
- adviser, referee, or editor feedback;
- data-engineering and replication experience.

GitHub stars are not sufficient evidence of methodological quality. External skills may be studied and adapted, but must not be copied wholesale without review.

## 2. Required update assessment

Before changing PERW, Codex must internally complete:

```text
PERW_UPDATE_ASSESSMENT

SOURCE:
PROBLEM:
PROPOSED_CHANGE:
GENERALIZABILITY:
FIT_WITH_USER:
BENEFIT:
COST:
CONFLICT:
ACTIVE_PROJECT_IMPACT:
EVIDENCE:
CLASSIFICATION: PATCH / MINOR / BREAKING
DECISION: ADOPT / HOLD / REJECT
```

The assessment must determine whether the proposal:

- solves a real weakness in the current PERW;
- generalizes across empirical-finance projects rather than one paper;
- fits the user's long-term focus on empirical finance, corporate finance, and fintech; SSCI Q2 or better; moderate workload; obtainable data; credible identification; and no method stacking to rescue weak projects;
- improves efficiency, identification quality, data quality, writing quality, review survival, or reproducibility;
- adds justified complexity and does not conflict with existing rules;
- could affect an active paper's treatment, estimand, outcome, sample, identification, gate decision, or Paper Scope;
- is supported by inspectable evidence.

Only `DECISION: ADOPT` permits a PERW modification.

## 3. Update classes

### PATCH

Text clarification, link repair, formatting, non-substantive template improvement, or explanatory improvement that does not change research decisions.

Codex may assess, modify, test, commit, and push automatically.

### MINOR

A new optional protocol or template, non-breaking audit, auxiliary gate check, or improved agent-collaboration rule. It must not change an existing paper's core identification.

Codex may assess, modify, test, commit, and push. The update report must state whether active papers should adopt it.

### BREAKING

Any change to stage structure, gate-passing criteria, treatment or estimand principles, identification rules, primary-outcome selection logic, agent research authority, scope-freeze principles, or Stop/Go rules.

Codex must not apply a breaking change automatically. It must:

1. generate `PERW_UPDATE_ASSESSMENT`;
2. stop before modification;
3. explain why the change may be worthwhile;
4. wait for explicit user approval;
5. update only after approval.

## 4. Keep paper-specific rules out of PERW

A rule that applies only to one paper must remain in that paper's project files. It must not enter PERW merely because it was useful once.

For example, a paper-specific sample cutoff must not become a PERW rule. A general requirement to audit treatment contamination when a policy expands nationally may qualify after assessment.

## 5. Active projects do not migrate automatically

A central PERW release does not silently change an ongoing paper's adopted version. If a new rule may affect an active design, produce:

```text
PERW_MIGRATION_ASSESSMENT

PROJECT:
CURRENT PERW VERSION:
PROPOSED PERW VERSION:
AFFECTED DESIGN OBJECTS:
WHAT REMAINS VALID:
WHAT REQUIRES REASSESSMENT:
BENEFIT:
COST / RISK:
RECOMMENDATION:
DECISION REQUIRED: YES
```

The user or ChatGPT decides whether the paper migrates.

## 6. Required update report

After every actual PERW update, Codex must briefly report:

```text
PERW UPDATED

OLD VERSION:
NEW VERSION:
WHY:
WHAT CHANGED:
FILES CHANGED:
CLASSIFICATION: PATCH / MINOR / BREAKING
ACTIVE PAPER IMPACT: None / Optional / Migration required
RESEARCH BENEFIT:
ROLLBACK:
```

Do not provide a long diff unless the user requests one.
