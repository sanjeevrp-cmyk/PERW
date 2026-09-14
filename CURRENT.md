# PERW Current Release

CURRENT_VERSION: **v2.0**
STATUS: **stable**
BREAKING_CHANGE_FROM_v1.2: **YES — research domain, early-stage architecture, routed gates, scope contract, and Stop/Go logic generalized**
WORKFLOW_ENTRY: `core/WORKFLOW.md`
PRINCIPLES: `core/PRINCIPLES.md`
ROLE_ROUTING: `core/ROLE_ROUTING.md`
CHANGELOG: `CHANGELOG.md`

PERW supports controlled continuous improvement. Proposed changes must first pass `protocols/workflow_update_governance.md`; external ideas and project-specific experience are never adopted without assessment.

## v2.0 breaking change

PERW now supports multiple empirical research architectures. Policy/shock is no longer mandatory; gates route by Claim Type and Evidence Architecture; causal identification remains mandatory whenever a causal claim is made; and viewpoint, measurement/new-fact, and regional/spatial pathways now have explicit validity standards. Stage 5 is now the Evidence & Identification Blueprint.

## Agent loading rule

For a **new empirical-paper project**, use the current stable PERW version.

For an **ongoing project**:
1. use the PERW version already adopted by that project if it is recorded locally;
2. if no version is recorded, load the current stable version and state that choice;
3. never silently migrate an ongoing project across a breaking change.

## Minimal load sequence

1. Read this file.
2. Read `core/PRINCIPLES.md`.
3. Read `core/ROLE_ROUTING.md`.
4. Read `core/WORKFLOW.md`.
5. Load only the stage / gate / protocol files needed for the current task.
6. Before modifying PERW itself, read `protocols/workflow_update_governance.md`.
