---
name: Tailwind UI style
---

- Follow the repository's existing Tailwind and design patterns.
- Prefer utility classes over custom CSS when the existing codebase does the same.
- Reuse existing component patterns, spacing scales, and layout conventions before creating new ones.
- Keep class lists readable and grouped in a consistent order.
- Avoid unnecessary wrapper divs and deeply nested markup.
- Prefer responsive, mobile-first layouts.
- Preserve existing color, typography, spacing, and dark-mode conventions unless explicitly requested.
- Do not introduce one-off visual styles if an existing utility pattern already solves the problem.
- Keep interactive states clear, including hover, focus, active, disabled, and error states.
- Prefer semantic HTML first, Tailwind second.
- When updating UI, keep diffs minimal and avoid unrelated visual churn.