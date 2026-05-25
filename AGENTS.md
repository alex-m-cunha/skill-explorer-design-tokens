# AGENTS.md

## Project Purpose

This repository documents the Skill Explorer Design Tokens v1.0 system for Nova SBE Executive Education's Brightspace Catalog and LMS implementation.

The documentation page defines a lightweight design-token and implementation-guidelines system for consistent, accessible, and maintainable Brightspace learning experiences.

## Scope

This is a documentation-first repository. Keep it lightweight.

Do not add frameworks, build systems, package managers, bundlers, or unnecessary tooling unless explicitly requested. The current static-site setup is intentional and should remain simple.

## File Conventions

- Keep the main documentation page as `index.html`.
- Do not rename `index.html`.
- Keep styles inline in `index.html` for now unless explicitly asked to refactor.
- Preserve the static-site structure used by GitHub Pages.
- Do not introduce generated assets unless they are required for a specific requested change.
- Treat `index.html` as the source of truth for the published documentation.

## Design-Token Rules

- `#2C2C2C` is the primary black.
- `#FFFFFF` is the base white.
- `#009BD0` is the official Nova Executive brand color.
- Do not use `#009BD0` as the default color for small links or body text on white.
- Use `#0077A3` for accessible links and interactions.
- Use Playfair Display for editorial and narrative headings.
- Use Open Sans for functional headings, body copy, micro-copy, captions, instructions, labels, and interface text.
- Use font weight `400` for normal reading.
- Use font weight `600` for headings, labels, and emphasis.
- Choose typography by the role of the content, not only by the `H1` / `H2` / `H3` level.

## Theme Customization Rules

Client or cohort customization should be limited to:

- one primary color;
- one logo;
- one LMS cover image;
- one banner image per Unit of Learning.

Logos and images are implementation assets, not core tokens, unless they are directly consumed by CSS or HTML.

## Brightspace Asset Rules

- UA banner optimal upload size: `2400 x 960 px`.
- UA banner minimum / standard size: `1200 x 200 px`.
- Actual desktop display area: approximately `1170 x 200 px`.
- Keep important content in the center safe zone.
- Avoid baked-in text.
- Prefer JPG for compatibility.
- PNG is acceptable when needed.
- Avoid square or vertical images for banners.

## Editing Rules

- Preserve accessibility and semantic hierarchy.
- Do not use headings for visual size only.
- Keep documentation concise and implementation-oriented.
- Avoid over-engineering the token system.
- Use placeholders instead of invented graphics, charts, or images.
- Do not add proprietary or sensitive Nova/client content unless it has been explicitly provided and cleared.

## Validation

This is a static HTML repository.

After editing:

- Open `index.html` locally in a browser if possible.
- Check that the page still renders correctly.
- Check responsive behavior at desktop and mobile widths.
- Check that GitHub Pages will still work from root-level `index.html`.

## Git / Commit Guidance

- Use clear commit messages.
- Keep commits focused.
- Mention token changes explicitly when relevant.
