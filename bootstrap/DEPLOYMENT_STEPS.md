# Deployment Steps

Canonical repository: `https://github.com/sanjeevrp-cmyk/PERW`

## 1. GitHub
Use the **public** repository above and upload the contents of this package at the repository root. Do not place unpublished paper projects, data, results, or private notes in it. Recommended first tag/release: `v1.1`.

## 2. ChatGPT
In the single ChatGPT Project, keep a short project instruction derived from `bootstrap/CHATGPT.md`. Paper projects remain in chats/files as before; they do not need to live in GitHub.

## 3. Codex
Configure a user/global Codex instruction with `bootstrap/CODEX.md`. Each paper keeps its own local folder exactly as before. A paper-specific AGENTS.md is optional and contains only project-specific rules, not another copy of PERW.

## 4. Hermes
Place `bootstrap/HERMES_RESEARCH.md` only in the Hermes **Research Profile** instructions. Other Hermes profiles must not load PERW.

## 5. Updating PERW
Edit only the GitHub workflow repository. For each release update CURRENT.md and CHANGELOG.md, and mark whether the change is breaking. New paper projects use current stable PERW; ongoing projects do not silently migrate across breaking changes.
