# Pax Dei Atlas 0.932 Beta

12 November 2026

A beta tracking update for invited Windows 10/11 x64 testers. The riding marker no longer freezes when you look back, tracking recovers better after Atlas restarts or loses focus, and the named card illustrations are back.

[Download the Windows installer](https://github.com/jayfunkdown/pax-dei-atlas-downloads/releases/download/v0.9.32/Pax-Dei-Atlas-Setup-0.9.32-x64.exe) · [Tester instructions](https://github.com/jayfunkdown/pax-dei-atlas-downloads/blob/main/BETA-TESTING.md)

## Install or update

Existing testers: use **Settings → Updates**, or close Atlas and run the official Setup over your existing installation. No uninstall is needed. Saved access, settings, pins and watches are retained. This is a required pre-1.0 beta update when offered through the beta updater. It is a full installer download of about 1.7 GB, because it includes all the named card illustrations again.

New testers: run Setup and enter your privately supplied beta access code. Log into Pax Dei and open the game map with your player arrow visible to establish position. Keep codes private. Discord is optional for downloading and using Atlas. This beta installer is not Windows publisher-signed; use the official download above.

## Riding and auto-path

- Fixed the riding marker freezing when you turn the camera to look behind you. Atlas now keeps your travel direction separate from the camera, so a rear view, an unreadable compass or switching away from the game keeps the marker moving forward for a limited time (up to 4 minutes or 3 km) until a fresh reading confirms where you are.
- Pressing Y on horseback starts auto-path in the direction you are facing, and at junctions the road is chosen from the way you have been travelling, not from a sideways camera.
- Pressing W, A, S or D to take over from auto-path stops the auto-path marker.
- An auto-travelling marker keeps moving along its road through a night-time compass blackout.
- A position reading during auto-path can no longer throw the marker far off the road you are travelling.

## Tracking recovery

- Better recovery after Atlas restarts or loses focus: tracking picks up again from agreeing landmark readings after a restart, a tracking startup problem no longer stops your saved access from being restored, and game-log reading catches up straight away.
- When you stand still the marker stays put, and a single stray reading cannot make it jump more than 40 m. Opening the game map (M) always gets the marker out of a stuck spot.
- Compass readings with only two points of interest can now correct the marker in small steps instead of being ignored, and close readings no longer start a phantom auto-run.
- Game-map (M) reads now also work when the map is zoomed out.
- Ports within the same province, such as Dolavon to Aven, are accepted when the area name changes, instead of the marker staying at the departure point.
- Indoors on foot, a faint guide-line reading no longer starts auto-path and walks the marker away.
- Fixed a short display lag after the marker finishes moving into place.

## Maps and route trace

- The main map keeps following you while you move.
- The red route trace keeps drawing when you cross a zone border.
- Lyonesse Wildlands: the main map no longer shows blank tiles, and the minimap stays centred on you.

## Named encounters

- Named card illustrations are back. All 991 card images from 0.929 ship again; 0.930 and 0.931 left them out, so cards showed no illustration.
- 54 named enemies that have no illustration of their own now use the closest existing official illustration.
- Named encounter cards can now appear while your position near a border is still being estimated.

## Known beta limits and feedback

Auto-pathing and tracking are still buggy. If the marker goes wrong, press M to reset tracking. Tracking remains approximate. Some roads are not mapped yet, so auto-path can leave the road where the map has no road data, and road forks are still being tuned. Horse speeds and mount detection are calibrated from limited live testing; other resolutions and UI scales may need more work. There is no indoor position tracking.

Market data updates hourly and may include sold stock. Named encounters indicate possible spawns, not live presence. For bugs, include the time, Atlas version, whether you were on foot or riding, whether you used Y auto-path, the road or junction involved, and whether M corrected it. Remove access codes, private room codes and unrelated chat from screenshots.
