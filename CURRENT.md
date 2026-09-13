# PERW Current Release

CURRENT_VERSION: **v1.1**  
STATUS: **stable**  
BREAKING_CHANGE_FROM_v1.0: **YES — agent-role and handoff architecture added**  
WORKFLOW_ENTRY: `core/WORKFLOW.md`  
PRINCIPLES: `core/PRINCIPLES.md`  
ROLE_ROUTING: `core/ROLE_ROUTING.md`  
CHANGELOG: `CHANGELOG.md`

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
