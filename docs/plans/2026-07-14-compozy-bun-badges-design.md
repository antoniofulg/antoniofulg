# Compozy and Bun badge design

## Goal

Add Compozy and Bun to the GitHub profile README's existing flat badge row.

## Compozy

Compozy is not present in the Simple Icons catalog, so a normal Shields.io
`logo=compozy` parameter cannot display its mark. Add a local composite SVG
badge under `assets/` that combines the official Compozy symbol with its name.
Link the badge to the official Compozy repository.

The badge should match the height, flat shape, typography, and restrained scale
of the existing Shields.io badges. Preserve the official symbol rather than
redrawing it.

## Bun

Use a standard flat Shields.io badge with the official `bun` Simple Icons logo.
Keep it next to the other runtime and framework badges.

## Verification

Confirm that the README renders both images at badge height, all image sources
resolve, the Compozy link points to `https://github.com/compozy/compozy`, and the
repository has no whitespace errors.
