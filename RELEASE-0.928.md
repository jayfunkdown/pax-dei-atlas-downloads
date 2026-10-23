# Pax Dei Atlas 0.928 Beta

24 October 2026

A beta tracking update for invited Windows 10/11 x64 testers, focused on road auto-path, riding and more reliable map reads.

[Download the Windows installer](https://github.com/jayfunkdown/pax-dei-atlas-downloads/releases/download/v0.9.28/Pax-Dei-Atlas-Setup-0.9.28-x64.exe) · [Tester instructions](https://github.com/jayfunkdown/pax-dei-atlas-downloads/blob/main/BETA-TESTING.md)

## Install or update

Existing testers: use **Settings → Updates**, or close Atlas and run the official Setup over your existing installation. No uninstall is needed. Saved access, settings, pins and watches are retained. This is a required pre-1.0 beta update when offered through the beta updater.

New testers: run Setup and enter your privately supplied beta access code. Log into Pax Dei and open the game map with your player arrow visible to establish position. Keep codes private. Discord is optional for downloading and using Atlas. This beta installer is not Windows publisher-signed; use the official download above.

## Road auto-path and auto-run

- Y auto-path follows the road on foot and on horseback, including at junctions and T-junctions, and picks the road back up after a position fix.
- On-foot auto-run fixed: pressing Y on foot moves the marker again.
- Auto-run continues while Atlas or the game loses focus or chat is open, and survives opening the game map (M).
- The marker stops when you stop, and facing alone no longer steers it.

## Riding

- Atlas detects when you are mounted from the HUD mount icon and uses horse walking, running and sprinting speeds, including the stamina-limited sprint.
- Speed on roads is modelled separately from open ground.
- While mounted, fresh landmark readings can re-acquire your position instead of being held back by an older anchor or a border.

## Map reads and recovery

- Fixed the marker staying stuck on a border after porting to a PvP gate.
- Game-map (M) reads lock onto the player arrow, not map artwork, UI panels or the frame, and need two agreeing frames before moving the marker. Readings near map corners recover correctly.
- Fixed freezes after opening the map and when crossing area borders; dead-reckoning continues through province-area borders.
- A wrong tower or white-icon re-anchor is rejected unless the evidence agrees.
- "Drifted into Wildlands" is no longer shown when the marker is already in that Wildlands.

## Smaller updates

- Map artwork now ships outside the main app archive, so future updates can be smaller and faster to apply.

## Known beta limits and feedback

Tracking remains approximate. Some roads are not mapped yet, so auto-path can leave the road where the map has no road data, and road forks are still being tuned. Horse speeds and mount detection are calibrated from limited live testing; other resolutions and UI scales may need more work. If tracking stalls, opening the game map with a clear player arrow remains a manual recovery option. There is no indoor position tracking.

Market data updates hourly and may include sold stock. Named encounters indicate possible spawns, not live presence. For bugs, include the time, Atlas version, whether you were on foot or riding, whether you used Y auto-path, the road or junction involved, and whether M corrected it. Remove access codes, private room codes and unrelated chat from screenshots.
