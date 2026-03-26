---
name: SvelteKit verification
---

- Prefer targeted verification over broad full-project runs.
- Prefer checking the nearest relevant route, component, or module first.
- Prefer linting only touched files before running broader checks.
- Prefer type-checking the project when changes affect routes, load functions, actions, stores, or shared types.
- Prefer running the smallest relevant test scope if tests exist.
- Use the repository's existing package manager and scripts.
- State clearly which verification steps were run and which were not run.
- If a command is expensive or likely to touch unrelated areas, note that before recommending it.