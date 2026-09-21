---
name: travel-journal-site
description: Design, build, and refine destination journal pages for a self-driving travel website. Use when adding a destination, changing its visual theme, integrating a route map with editorial content, or reviewing interactions and responsive behavior.
---

# Travel Journal Site

Create immersive destination journals that feel like parts of one coherent travel website rather than unrelated tourism landing pages.

## Working approach

1. Inspect the existing project structure, design language, and components before editing.
2. Preserve the project's current framework and established conventions unless a change is necessary for the requested result.
3. Identify the destination's natural character and develop a fitting visual theme.
4. Keep shared navigation, typography, spacing, and content structure consistent across destinations.
5. Integrate the route map into the editorial composition instead of treating it as an isolated rectangular widget.
6. Verify desktop and mobile behavior after implementation.

## Visual direction

- Favor a restrained, cinematic, editorial style.
- Use photography, typography, terrain colors, ambient texture, and subtle motion to establish atmosphere.
- Give each destination an identifiable personality without making it feel like a separate website.
- Avoid excessive glass effects, glowing controls, decorative gradients, and motion without purpose.
- Keep text readable over maps and imagery.
- Respect `prefers-reduced-motion`.

## Destination themes

Select colors, textures, imagery, and motion from the destination's landscape and travel experience. Treat the following as starting points, not rigid presets.

### Yichun — forest

- Palette: pine green, moss, fog grey, and warm wood.
- Visual motifs: forest canopy, contour lines, mist, and quiet roads.
- Motion: slow parallax and soft pointer disturbance.
- Map treatment: subdued roads over deep green terrain.

### Dalian — coast

- Palette: sea blue, sand, white, and restrained sunset coral.
- Visual motifs: coastline, waves, sea wind, and harbor lights.
- Motion: gentle horizontal drift and tide-like transitions.
- Map treatment: pale coastal terrain with an emphasized shoreline.

For a new destination, derive a distinct theme from its real geography and travel narrative while retaining the site's shared design system.

## Map integration

- Treat the map as part of the page canvas or background composition.
- Blend the boundary between content and map with spatial overlap, masks, gradients, terrain colors, or restrained overlays.
- Preserve the usability of markers, routes, labels, zoom controls, and pointer gestures.
- On small screens, prioritize content readability and intentional map interaction.
- Use reference websites only for design principles; do not copy protected source code, text, or visual assets.

## Interaction and performance

- Use animation to clarify navigation, geography, progress, or atmosphere.
- Prefer lightweight CSS and platform capabilities before adding a new dependency.
- Keep pointer effects subtle and disable or simplify them for touch devices.
- Avoid effects that cause layout shifts, scroll jank, excessive GPU use, or inaccessible controls.

## Verification

After changes, check:

- Common desktop and mobile widths.
- Navigation, map controls, route markers, scroll effects, and pointer interactions.
- Text contrast, keyboard access, reduced-motion behavior, and touch usability.
- Obvious console errors and performance regressions.

Summarize the files changed, the design decisions made, and any remaining limitations.
