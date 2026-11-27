# CLAUDE.md — fresh-adventure-fe

Authoritative AI execution protocol for this repository (decision D-001). Claude Code is the designated AI coding tool.

## Repository

- Name: `fresh-adventure-fe` (Public)
- Role: Frontend repository — user interface, dashboard, and BI data visualization.
- Shared project documentation is canonical in the main repository: https://github.com/AI-Campus-1st/fresh-adventure

## Read Before Work

1. `docs/SHARED_CONTEXT.md` — approved shared context snapshot (source versions and commit). If it is missing or outdated, say so and ask for the required context. Do not assume content from other repositories.
2. `README.md` and `docs/README.md` — repository structure and local documentation.

## Essential Rules

1. Classify each task by risk level (RULES.md §4). Level 3 work requires explicit human approval before execution. When uncertain, use the higher level.
2. Never commit, push, merge, or deploy without explicit authorization. Commit authorization does not imply push authorization.
3. Never read, print, copy, or summarize actual secret values. Do not open `.env` or other secret-bearing files. Use non-disclosing checks (file existence, variable presence).
4. Do not install dependencies or initialize frameworks until the technology stack (TECHSTACK) is approved.
5. Do not change the approval status (`DRAFT`, `PROPOSED`, `APPROVED`, `SUPERSEDED`) of any document. Approval is a human decision.
6. Do not treat drafts, proposals, or AI-generated suggestions as approved decisions. Check each document's Status field.
7. Do not duplicate definitions owned by another document (for example, Golden Time in PTS §8). Link to the source instead.
8. Report actual results only. Never fabricate file contents, data, test results, or completion status. Report failures and limitations.
9. Preserve unrelated work and other contributors' changes. Inspect the branch and working tree before editing.
10. Follow Git conventions in the main repository's `docs/conventions.md`.

## Repository-Specific Rules

- This repository is public. Never place API keys, tokens, or credentials in browser-side code, public environment variables, or build artifacts.
- Call external services only through the backend.
- Display analytical results from the backend. Do not calculate or redefine authoritative analytical results in the frontend.
- The `src/` structure is provisional until TECHSTACK is approved. `src/app/` and `src/pages/` coexist until the routing approach is decided.
