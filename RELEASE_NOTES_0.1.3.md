# AI Usage Battery 0.1.3 (Build 4)

This release improves the Sparkle update experience.

## Highlights

- Enables Sparkle automatic update checks explicitly in the app bundle.
- Enables Sparkle automatic update downloads by default.
- Sets the scheduled automatic update check interval to one hour.

## Fixes

- Prevents the Sparkle automatic update permission prompt from interrupting the first manual `Check for Updates` flow.
- Makes direct-distribution update behavior more predictable for users updating from older builds.

## Verification

- `swift test` passes.
- Release app signing, notarization, stapling, Gatekeeper assessment, DMG generation, and DMG verification were run for this build.
