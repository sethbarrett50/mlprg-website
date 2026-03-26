---
name: ESLint and Prettier
---

- Prefer fixing lint issues in touched files rather than doing broad repo-wide cleanup.
- Prefer formatting only edited files unless explicitly requested.
- Follow the repository's existing ESLint and Prettier configuration.
- Do not disable lint rules unless explicitly requested or clearly justified.
- Prefer code changes that satisfy lint rules over inline ignores.
- If an ignore is necessary, keep it narrow and explain why.
- Preserve existing import ordering and formatting conventions.
- When proposing verification commands, use the repository's package manager and scripts.
- State clearly which checks were run and which were not run.
- If a full lint or format pass would create broad unrelated diffs, avoid it unless explicitly requested.