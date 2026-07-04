# Skill Explorer Design Tokens v1.0

Public documentation for the Skill Explorer design-token and implementation-guidelines system for Nova SBE Executive Education.

This repository is intentionally lightweight and is designed to be published through GitHub Pages. It contains only the public-facing token documentation and static Brightspace page examples required for continuity of access.

## Scope

This documentation covers:

- core color tokens;
- Nova Executive brand color usage;
- accessible link and interaction colors;
- typography rules;
- heading usage by function;
- theme customization boundaries;
- LMS cover image requirements;
- Unit of Learning banner image requirements;
- base page-template examples;
- implementation-oriented CSS custom properties.

## Public-package boundary

This public repository does not include catalogue prototypes, email communications, source spreadsheets, meeting notes, screenshots, or confidential implementation material.

Those materials should live in separate private repositories or private handoff channels.

## Implementation principle

The system is intentionally lightweight. Client or cohort customization should only change:

- one primary color;
- one logo;
- one LMS cover image;
- one banner image per Unit of Learning.

The underlying structure, typography, accessibility rules, and template logic should remain consistent.

## GitHub Pages

This repository is intended to be published from the root of the `main` branch.

The main documentation file is:

```text
index.html
```

