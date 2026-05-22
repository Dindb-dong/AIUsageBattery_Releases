# AI Usage Battery 0.1.1 (Build 2)

This release turns AI Usage Battery into a usable direct-distribution macOS app with signed release artifacts, Sparkle update support, and a more complete menu bar/settings experience.

## Highlights

- Adds a real Xcode project workflow for local debugging and release builds.
- Adds Sparkle 2.9.2 to the macOS app target so in-app update checks are available in direct-distribution builds.
- Ships notarized Developer ID release artifacts: `.app`, `.zip`, and `.dmg`.
- Adds a polished drag-to-Applications DMG layout.
- Adds the generated app icon assets and Finder/app bundle icon metadata.

## Usage Tracking

- Improves Codex usage detection from local rate-limit metadata.
- Improves Claude usage detection from transcript estimates, statusline capture data, and probe fallbacks.
- Adds shared provider selection so menu bar, popover, and settings stay in sync.
- Adds active account display for Codex and Claude where local metadata is available.

## App Experience

- Adds onboarding for first launch setup.
- Adds notification permission and threshold notification controls.
- Adds settings for provider display, menu bar meter style, usage window selection, refresh cadence, diagnostics, privacy, license, and updates.
- Adds a Quit action in both the menu bar popover and settings.
- Fixes menu bar battery coloring and provider toggle behavior.

## Release Notes

- Sparkle appcast feed: `https://raw.githubusercontent.com/Dindb-dong/AIUsageBattery_Releases/main/appcast.xml`
- Download the DMG for normal installation.
- Sparkle update installation should be tested from an older installed build once a newer appcast entry is available.
