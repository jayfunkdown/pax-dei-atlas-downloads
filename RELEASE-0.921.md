# Pax Dei Atlas 0.921 Beta

[Download for Windows x64](https://github.com/jayfunkdown/pax-dei-atlas-downloads/releases/download/v0.9.21/Pax-Dei-Atlas-Setup-0.9.21-x64.exe)

This beta combines the first round of tester feedback with better diagnostic reporting.

- Named cards are about 10% smaller and use a five-minute cooldown for each location. The visible frame stays anchored above the health bar.
- Dungeon cards require repeated recognition of the interior location tag. Approaching an entrance alone does not trigger them. Atlas uses the nearby overworld entrance to identify the dungeon, fades through an entering screen, and keeps the dungeon map visible until overworld tracking returns. The minimap shows the dungeon name and explains that indoor tracking is unavailable.
- Change your display name while already in a party. Reconnect automatically after connection loss, and restore a recently joined room after restarting Atlas, provided the room still exists. Party names and distances are larger and closer together.
- Route tracing uses a narrow gold line with a dark outline. The inactive Custom minimap-size option has been removed.
- Overlay positions follow changes to the game window and resolution. Minimap stacking recovery has been improved for returning to fullscreen gameplay.
- Missing card pictures show a loading/unavailable state and retry, with a diagnostic event if loading fails.
- Automatic fault reports, recovery reports and session reports help investigate crashes and tracking problems. When closing Atlas, choose **Send report & close**, **Close without a report**, or **Cancel**. **Always send automatically** is available.

## Installing or updating

Use **Settings → Updates** in Atlas, or close Atlas and run the official Setup linked above. Saved preferences and valid beta access should carry over. New testers need a private access code from the owner; no email is requested. Match the game's UI-size preset in Atlas, then open the game map with your player arrow visible to establish position.

The installer is branded but is not Windows publisher-signed yet. Windows may show an unknown-publisher or reputation prompt. Download only from the official release.

## Reporting and privacy

Beta reporting is enabled by default and can be disabled in **Settings → Privacy**. Useful technical context includes Windows, CPU/GPU and driver versions, memory, resolution, scale, refresh rate, game-window dimensions, feature use and sanitized errors. Personal files, names, chat, access codes, screenshots, exact positions and routes are excluded. Usage reports are retained privately for up to 90 days; technical diagnostics for up to 30 days. Failed uploads retry on a later connected session when reporting is enabled.

## Known limits and testing focus

The original tester crashes have not yet been traced to a confirmed cause. Improved reporting is intended to provide evidence from future failures. Tracking can still drift or pause, including delayed recovery near area boundaries; opening the game map can help. Dungeon transitions and exclusive-fullscreen overlay behavior need further real-game testing. Party recovery requires the original room to remain available. Named cards describe possible spawns, not live enemy presence.

The public version is **0.921 Beta**; the installer and update system use **0.9.21** internally.

[Tester guide](BETA-TESTING.md) · [Features and screenshots](FEATURES.md) · [Discord](https://discord.gg/YjJxCBbeJU)
