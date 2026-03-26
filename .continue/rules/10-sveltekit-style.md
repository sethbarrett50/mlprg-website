---
name: SvelteKit style
---

- Follow the repository's existing SvelteKit structure and conventions.
- Use current Svelte patterns and avoid legacy syntax unless the repository already uses it.
- Prefer small, focused components over large multi-purpose files.
- Keep page and layout files thin; move reusable logic into nearby modules when appropriate.
- Prefer server-side loading and form actions when they fit the existing app architecture.
- Do not introduce unnecessary client-side state or browser-only logic into server code.
- Preserve route structure, load behavior, and data flow unless a change is explicitly requested.
- Prefer explicit prop and return typing where the surrounding codebase uses TypeScript.
- Reuse existing components, stores, utilities, and helpers before creating new abstractions.
- Keep accessibility in mind: use semantic HTML, proper labels, and keyboard-friendly interactions.
- Preserve existing error/loading UX patterns unless a change is explicitly requested.
- Avoid adding new dependencies unless explicitly requested.