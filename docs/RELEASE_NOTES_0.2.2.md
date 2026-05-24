# AI Usage Battery 0.2.2 (Build 6)

This release tightens account detection, reset timing, refresh behavior, and support surfaces for Codex and Claude users.

## Changes

- Shows the Codex account email from local auth metadata instead of only the opaque account id.
- Reads Codex and Claude reset timestamps from provider metadata when available, including full date and time in the popover.
- Ignores stale Claude statusline reset data so expired windows are not shown as current limits.
- Makes the popover refresh button run the local probe and apply updated usage data immediately.
- Adds popover account-switch buttons that open Codex or Claude login flows in Terminal.
- Removes noisy missing Codex source paths from settings diagnostics.
- Replaces the About repository row with a report issue button linked to the public release repository.
- Adds structured bug report and feature request templates to the public release repository.

## Verification

- Swift test suite passes.
- Release build is Developer ID signed with hardened runtime.
- Notarization, stapling, Gatekeeper assessment, zip payload signature verification, DMG verification, and Sparkle appcast signing are part of the release flow.
