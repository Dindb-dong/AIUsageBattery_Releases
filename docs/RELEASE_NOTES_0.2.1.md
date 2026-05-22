# AI Usage Battery 0.2.1 (Build 5)

This release expands AI Usage Battery from a single-provider meter into a customizable Codex and Claude menu bar dashboard.

## Highlights

- Adds Codex-only, Claude-only, and dual-provider menu bar display modes.
- Adds 5-hour, 1-week, and dual-window menu bar display modes when a single provider is selected.
- Shows both 5-hour and 1-week cards in the popover, using a 2x2 layout when Codex and Claude are both selected.
- Adds reset timing to usage cards when local sources expose reset data.
- Adds customizable menu bar colors, split percentage colors, split percentage font size, and remaining-limit thresholds.
- Converts onboarding into a polished first-run checklist with language selection and localized checklist text.
- Defaults new installs to English while still allowing Korean or system language.

## Fixes

- Removes activity event counts, token/message estimates, source descriptions, and confidence badges from the primary popover cards.
- Installs the usage probe helper from the app bundle into Application Support for packaged builds, with a development-path fallback.
- Carries reset timing through rate-limit, probe, transcript, cache, and fallback snapshot paths.
- Removes the unnecessary Full Disk Access onboarding action that could lead macOS to show an unrelated privacy prompt.

## Verification

- `swift test` passes.
