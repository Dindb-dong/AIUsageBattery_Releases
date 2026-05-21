# AI Usage Battery 0.1.2 (Build 3)

This release improves the menu bar meter and makes the popover quicker to use.

## Highlights

- Replaces the old dot meter with a compact pie meter.
- Makes the pie meter the default menu bar style for new installs.
- Keeps existing `dots` settings compatible by restoring them as `Pie`.
- Renders the pie meter as an AppKit image so it appears reliably in the macOS menu bar.
- Keeps percentage text visible when `Show percentages` is enabled.
- Adds a `5 hours / 1 week` toggle directly inside the menu bar popover, below the provider toggle.

## Fixes

- Fixes the pie meter disappearing in the menu bar.
- Fixes the pie style hiding percentage text.
- Improves unavailable/unknown usage rendering so the menu bar still shows a visible meter outline.

## Verification

- `swift test` passes.
- Release app signing, notarization, stapling, Gatekeeper assessment, DMG generation, and DMG verification were run for this build.
