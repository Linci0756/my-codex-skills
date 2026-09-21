# Shared Design System

Use this reference when changing shared layout, typography, maps, interactions, responsive behavior, or performance-sensitive effects.

## Core visual language

- Favor a restrained, cinematic, editorial style.
- Let photography, typography, terrain colors, ambient texture, and subtle motion establish atmosphere.
- Maintain clear hierarchy and generous breathing room.
- Avoid excessive glass effects, glowing controls, decorative gradients, and ornamental UI.
- Keep text readable over maps and imagery with sufficient contrast and stable overlays.

## Continuity across destinations

Keep these elements recognizable across all destination pages:

- Primary navigation and page transitions.
- Typography families and hierarchy.
- Spacing rhythm and content widths.
- Route, location, and journal metadata patterns.
- Control shapes, focus states, and interaction feedback.

Allow palette, imagery, texture, ambient motion, and map styling to adapt to each destination.

## Map composition

- Treat the map as a visual layer in the editorial composition, not a detached card.
- Use overlap, masks, gradients, or terrain-colored surfaces to blend content and map.
- Preserve route visibility, marker clarity, labels, zoom controls, and pointer gestures.
- Avoid placing essential prose under interactive map regions.
- On mobile, separate reading and map interaction when simultaneous use becomes cramped.

## Motion and pointer interaction

- Use motion to communicate navigation, geography, reading progress, or atmosphere.
- Keep pointer effects subtle and locally scoped.
- Simplify or disable hover-driven effects on touch devices.
- Respect `prefers-reduced-motion` and retain understandable state changes without animation.
- Avoid scroll hijacking and effects that compete with reading.

## Responsive and accessible behavior

- Design mobile behavior intentionally rather than merely stacking desktop sections.
- Maintain comfortable text size, line length, and touch targets.
- Preserve visible keyboard focus and logical tab order.
- Do not rely on color or animation alone to communicate meaning.
- Confirm overlays, maps, and navigation remain operable at narrow widths.

## Performance constraints

- Prefer CSS and existing project capabilities before adding dependencies.
- Avoid continuous pointer or scroll listeners when CSS or requestAnimationFrame-based updates suffice.
- Prevent layout shifts by reserving media and map dimensions.
- Reduce large blur layers, excessive compositing, and full-screen high-frequency effects.
- Lazy-load noncritical imagery and map features where appropriate.
