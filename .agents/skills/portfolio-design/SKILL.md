---
name: portfolio-design
description: Design and frontend rules for Ngọc Phương's Production Accounting and SAP portfolio.
---

# Portfolio Design Skill

Use this skill for homepage work, portfolio sections, typography, spacing, interactions, and responsive behavior.

## Design read

Treat the site as a professional knowledge portfolio for Finance/SAP hiring audiences.

The desired language is:
- modern
- precise
- high-trust
- calm
- editorial in hierarchy, but not fashion-editorial
- technically credible
- mobile-friendly

Do not make the site feel like a generic résumé template or an AI-generated SaaS landing page.

## Design dials

- DESIGN_VARIANCE: 6
- MOTION_INTENSITY: 4
- VISUAL_DENSITY: 5

Interpretation:
- enough asymmetry to feel designed
- restrained motion
- moderate information density suitable for knowledge content

## Layout rules

- Prefer asymmetric two-column compositions over centered hero layouts.
- Use CSS Grid for multi-column sections.
- Keep a readable max-width around 1180–1280px.
- On mobile, reduce to one clear reading column.
- Avoid rows of identical feature cards when another hierarchy communicates better.
- Knowledge content can be denser than marketing content.
- Do not force equal card heights when content naturally differs.

## Typography

- Prefer a modern sans-serif display system for headings.
- Use tight tracking for large headings and comfortable line-height for body text.
- Limit body copy width for readability.
- Use small labels sparingly; avoid excessive all-caps.
- T-codes and technical identifiers should use a monospace style.

## Color

- Use one accent family consistently.
- Use neutral or lightly tinted backgrounds.
- Avoid generic purple/blue AI gradients.
- Avoid abrupt unrelated dark sections in an otherwise light page; use tonal contrast from the same palette instead.
- Keep contrast accessible.

## Components

Every interactive control must have:
- hover state
- active/pressed feedback when appropriate
- visible keyboard focus
- adequate touch target on mobile

Avoid:
- decorative pills everywhere
- generic border + white-card + shadow on every section
- dead buttons
- icons used only as decoration
- excessive rounded rectangles

## Motion

Motion should clarify hierarchy:
- subtle reveal on entry
- short hover transitions
- no constant looping animation
- no heavy parallax on knowledge content
- respect `prefers-reduced-motion`

## Responsive checks

At minimum verify:
- 360px
- 390px
- 768px
- 1024px
- wide desktop

Check:
- no horizontal overflow
- mobile menu works
- search field remains usable
- filters can scroll horizontally if needed
- language switch remains reachable
- text never becomes too small

## Completion check

Before finishing a visual change:
- compare before/after
- check VI and EN
- check mobile and desktop
- confirm all interactions still work
- verify deployment after commit

## Reference

Adapted for this project from design principles found in:
https://github.com/Leonxlnx/taste-skill
