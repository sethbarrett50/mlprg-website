---
name: SvelteKit repo boundaries
---

- Do not rename routes, move files, or change package layout unless explicitly requested.
- Do not rewrite working components, stores, hooks, or utilities without a clear need.
- Preserve public component APIs, exported helpers, and route behavior unless explicitly requested.
- Avoid broad refactors across pages, layouts, and shared UI unless the request requires it.
- Preserve existing environment variable usage, adapter setup, and deployment-related configuration unless explicitly requested.
- Do not change generated files, build output, lockfiles, or package versions unless explicitly requested.
- Preserve existing Tailwind, ESLint, Prettier, and TypeScript config unless the request is specifically about tooling.
- When changing UI behavior, data loading, navigation, or form handling, call out user-visible behavior changes explicitly.
- Prefer minimal diffs that solve the requested problem directly.