---
name: travel-journal-site
description: Design, build, and refine destination journals and multi-stop route chapters for a self-driving travel website. Use when adding a destination, defining a place-specific theme, connecting several stops into one visual journey, integrating maps with editorial content, or reviewing travel-page interactions and responsive behavior.
---

# Travel Journal Site

Build destination chapters that feel distinct but remain part of one coherent travel website.

## Workflow

1. Inspect only the project files directly related to the requested journal, shared layout, and map.
2. Preserve the existing framework, components, navigation, typography, and spacing unless the task requires a change.
3. Read [references/design-system.md](references/design-system.md) only when changing shared UI, maps, motion, responsive behavior, or accessibility.
4. Read only the matching destination or route reference:
   - Yichun: [references/yichun.md](references/yichun.md)
   - Dalian: [references/dalian.md](references/dalian.md)
   - Datong–Ulanqab–Hohhot: [references/datong-ulanqab-hohhot.md](references/datong-ulanqab-hohhot.md)
5. For an unlisted destination, derive a concise theme from its real geography and journey narrative. Add a reference only when the theme will be reused.
6. Implement the smallest coherent change and run only the checks needed for affected behavior.

## Core constraints

- Treat the map as part of the editorial canvas, not an isolated rectangular widget.
- Give each destination a recognizable atmosphere without turning it into a separate website.
- Use motion to support navigation, geography, progress, or atmosphere.
- Keep map controls, text, keyboard navigation, touch behavior, and reduced-motion behavior usable.
- Avoid copying another site's protected code, text, or assets.
- Do not scan, rewrite, or test unrelated parts of the repository.

## Completion

Summarize changed files, key design decisions, checks performed, and remaining limitations. Keep the explanation concise.
