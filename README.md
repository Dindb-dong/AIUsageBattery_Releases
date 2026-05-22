# AI Usage Battery

AI Usage Battery is a local-first macOS menu bar app for tracking Codex and Claude usage limits.

It estimates remaining usage from local metadata and status information, then keeps the result visible beside the system clock. Prompt content and provider credentials are not uploaded.

![AI Usage Battery onboarding](assets/onboarding.png)

## What It Shows

- Codex and Claude usage in one menu bar app.
- 5-hour and 1-week usage windows.
- Remaining percentage, reset time when available, and latest local refresh status.
- Codex-only, Claude-only, dual-provider, and dual-window display modes.
- A first-run checklist for local data readiness, Claude statusline capture, usage probe setup, and privacy expectations.

## Menu Bar Modes

Show one provider, both providers, one limit window, or both limit windows depending on how you work.

| Provider split | Window split |
| --- | --- |
| ![Codex both-window popover](assets/codex-both.png) | ![Both providers one-week popover](assets/both-1week.png) |

Compact menu bar meters can use a battery-style indicator, a pie-style indicator, or percentages.

| Battery | Pie |
| --- | --- |
| ![Battery menu meter](assets/provider-battery.png) | ![Pie menu meter](assets/provider-pie.png) |

## Customization

The Settings window lets you tune both behavior and appearance:

- Choose whether the menu bar shows Codex, Claude, or both.
- Choose whether it shows the 5-hour limit, 1-week limit, or both windows.
- Pick battery, pie, or percentage display styles.
- Customize remaining-limit colors for healthy, medium, low, critical, and unknown states.
- Customize split percentage colors for Codex vs Claude and 5-hour vs 1-week displays.
- Adjust the split percentage font size.
- Set custom threshold percentages instead of using fixed 20/40/80 cutoffs.
- Configure refresh cadence and whether the bundled usage probe helper runs periodically.
- Configure local notifications for near-limit alerts.

| Menu bar settings | Color and threshold settings |
| --- | --- |
| ![Menu bar settings](assets/settings-menubar.png) | ![Menu color settings](assets/settings-menucolor.png) |

| Refresh settings | Notification settings |
| --- | --- |
| ![Refresh settings](assets/settings-refresh.png) | ![Notification settings](assets/settings-notification.png) |

## Download

Download the latest DMG from the [GitHub Releases page](https://github.com/Dindb-dong/AIUsageBattery_Releases/releases/latest).

Sparkle appcast feed:

```text
https://raw.githubusercontent.com/Dindb-dong/AIUsageBattery_Releases/main/appcast.xml
```

App repository:

```text
https://github.com/Dindb-dong/AIUsageBattery
```
