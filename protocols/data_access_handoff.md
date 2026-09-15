# Data Access / PI Data Handoff Protocol

Use this protocol only when a research task requires acquiring or receiving data. It separates execution access from scientific data feasibility and keeps PI involvement limited to genuine access barriers.

## 1. Access dimensions

Audit these separately:

1. whether the source or required information exists;
2. whether the PI/research team can legally obtain it;
3. whether Codex/Hermes can legally access it in the current execution environment;
4. whether delivered data actually satisfy provenance, field, coverage, measurement, matching, and sample-support requirements.

**Agent access failure ≠ PI access failure ≠ team data unavailability ≠ measurement failure ≠ scientific design failure.**

## 2. Standard access states

### AUTO_ACCESSIBLE

The executor can legally obtain the data from public sources, workspace files, authorized connectors, permitted APIs/scraping, or approved construction/matching. The executor acquires it autonomously and continues; it must not transfer avoidable mechanical collection work to the PI.

### ACCESS_BLOCKED_PI_REQUIRED

The source and need are identified, but the executor cannot legally access the data because of institutional login, paid subscription, 2FA, CAPTCHA, IP/VPN restriction, human licence confirmation, site rules, or another genuine legal/technical control. Pause the dependent branch and issue a precise `PI_DATA_REQUEST`. This state is not evidence that the paper or Data / Measurement Gate has failed.

### DELIVERED_PENDING_VALIDATION

The PI has delivered data, but actual fields and quality have not yet passed audit. The executor takes ownership of validation; delivery alone does not make the data usable.

### VALIDATED

The data have passed the relevant provenance, integrity, field, coverage, identifier, missingness, measurement, matching, and sample-support checks. The corresponding Gate may now use the verified evidence.

### TRULY_UNAVAILABLE

After reasonable investigation, the research team cannot obtain the necessary data legally within the research horizon, or the key construct/primary evidence is genuinely unobservable. Only this state may support a data-unavailability HOLD / NO-GO, together with the scientific evidence for that judgment.

## 3. Agent-first acquisition

Codex/Hermes should autonomously obtain data they can legally access, download, scrape, query through an API, locate in the workspace, receive through an authorized connector, construct, or match. Convenience is not a reason to ask the PI to do an executor's work.

Never bypass access controls, terms, paywalls, logins, CAPTCHA, or licence restrictions. Never request passwords, cookies, tokens, or other credentials. Never fabricate fields, silently substitute a materially weaker proxy, or run formal evidence production across a critical data gap.

## 4. Branch-level pause

When access is blocked, set:

`EXECUTION_STATUS: PAUSED_FOR_PI_DATA`

Pause every task whose scientific validity depends on the blocked data. Independent, low-cost, non-result-driven work may continue, such as public-source collection, required-field design, identifier crosswalks, documentation review, unaffected code scaffolding, and provenance documentation. Do not use parallel work to bypass the dependency.

The pause does not authorize changing the Core Question, Treatment, Outcome, Claim Type, Evidence Architecture, or another frozen design object.

If the blocked data are necessary for the current Gate, record the Data / Measurement Gate as `PENDING` or `NOT_YET_DECIDED`, not NO-GO. A separate scientific NO-GO remains possible only when independent evidence already establishes it; state that its basis is unrelated to access.

## 5. PI_DATA_REQUEST

Use `templates/PI_DATA_REQUEST.md`. Specify the database and module/sub-library, time and sample ranges, required information concepts, confirmed field names only, filters, export format, placement, resume point, and blocked/unblocked tasks. Do not issue a vague request for an entire database, and do not invent unknown field names.

## 6. Delivery, validation, and resume

On delivery, set `DELIVERED_PENDING_VALIDATION` and audit:

- file completeness and integrity;
- fields and coding;
- coverage and provenance;
- missingness and identifiers;
- construct/measurement validity;
- matching feasibility;
- sample and treatment/control support when applicable.

Set `VALIDATED` only after the relevant checks pass. If validation fails, report the observed deficiency and return to the Data / Measurement Gate; do not describe delivery as successful data access. If validation passes, resume from the recorded checkpoint without rerunning previously verified work that the new data cannot affect.
