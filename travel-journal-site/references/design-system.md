# Shared Design System

Read this file only when changing shared layout, maps, motion, responsive behavior, or accessibility.

## Visual continuity

- Favor a restrained, cinematic, editorial style.
- Keep navigation, typography hierarchy, spacing rhythm, journal metadata, map controls, and focus states recognizable across destinations.
- Adapt palette, photography, texture, ambient motion, and map styling to the place.
- Avoid excessive glass effects, glowing controls, ornamental gradients, and motion without purpose.
- Maintain stable text contrast over maps and images.

## Map composition

- Blend map and content through overlap, masks, gradients, terrain color, or restrained overlays.
- Preserve route visibility, markers, labels, zoom controls, and pointer gestures.
- Do not place essential prose beneath interactive map regions.
- On narrow screens, use intentional reading and map states rather than squeezing both together.

## Interaction

- Keep pointer effects subtle and locally scoped.
- Simplify or disable hover behavior on touch devices.
- Respect `prefers-reduced-motion` and retain understandable state changes without animation.
- Avoid scroll hijacking, layout shifts, and continuous high-cost effects.

## Performance and checks

- Prefer existing project capabilities and CSS before adding dependencies.
- Reserve dimensions for maps and media.
- Check affected desktop and mobile widths, keyboard focus, touch targets, map controls, console errors, and obvious regressions.
