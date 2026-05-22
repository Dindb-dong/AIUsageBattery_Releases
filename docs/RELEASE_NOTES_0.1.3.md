# AI Usage Battery 0.1.3 (Build 4)

This release improves the Sparkle update experience.

## Highlights

- Moves Sparkle's automatic update permission prompt to the first Settings window visit.
- Enables Sparkle automatic update downloads by default.
- Sets the scheduled automatic update check interval to one hour.

## Fixes

- Prevents the Sparkle automatic update permission prompt from interrupting a manual `Check for Updates` flow.
- Keeps manual update checks focused on finding/downloading the update instead of first asking about future automatic checks.
- Makes direct-distribution update behavior more predictable for users updating from older builds.

## Verification

- `swift test` passes.
- Release app signing, notarization, stapling, Gatekeeper assessment, DMG generation, and DMG verification were run for this build.
