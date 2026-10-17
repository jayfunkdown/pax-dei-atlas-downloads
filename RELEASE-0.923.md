# Pax Dei Atlas 0.923 Beta

A regular beta release for invited Windows 10/11 x64 testers.

[Download the Windows installer](https://github.com/jayfunkdown/pax-dei-atlas-downloads/releases/download/v0.9.23/Pax-Dei-Atlas-Setup-0.9.23-x64.exe) · [Installation and beta guide](https://github.com/jayfunkdown/pax-dei-atlas-downloads/blob/main/BETA-TESTING.md) · [Discord](https://discord.gg/YjJxCBbeJU)

## Install or update

New testers: download and run Setup, launch Atlas, then enter your privately supplied beta access code. Codes are supplied individually; never post them in Discord. Log into Pax Dei and open the in-game map with your player arrow visible to establish position.

Existing testers: use the update notice in Atlas. This regular pre-1.0 beta release is a required update when offered by a compatible client. You can also close Atlas and run the official Setup over your existing installation. Settings and valid saved access are retained. If an older beta closes without installing, run Setup manually and reopen Atlas. No uninstall is needed.

## Named encounters

- Surface encounters now leave a larger encounter-card replay icon inside their highlight for 15 minutes. Click it to replay the complete enemy/relic/crafting roster.
- Revisiting during that window does not automatically repeat cards. Replay does not extend expiry; after expiry the next approach can trigger again. Several discoveries can remain visible.
- Only one nearby dotted guide is shown. Replay clicks select its target; a newly triggered encounter takes over. Ordinary POI guides release beyond 100 metres.
- Named encounters no longer black out the minimap. The opaque encounter heading sits above the cards over the Medium stamina-bar position.
- Named cards use uniform bottom-centred positioning and resolution scaling across tiers, with safer caption spacing and improved first-display image preparation.
- Faster presentation: the old announcement wait is removed. An isolated test improved from about 4.15 seconds to 0.43 seconds for replay; actual timing depends on load and queued card groups.

## Dungeons

- Entrance proximity highlights the location but does not play dungeon cards.
- The confirmed interior Zone / Biome tag starts the identified dungeon roster once. Dungeon cards have no replay button.
- The minimap retains the dungeon status and the main map retains its dungeon reference view until fresh overworld tracking returns. Indoor position tracking is unavailable.

## Tracking, party and usability

- Improved recovery after respawning, compass reacquisition and border-area recognition, while retaining confirmation checks against large false corrections.
- Closing game chat with an outside click releases the chat pause.
- Compact one-line party members, clearer right-side party status and display-name editing while joined. Party connection recovery is retained.
- Ready and Wait placements match; named cards keep their independent bottom anchor.
- Gentler volume response, centred map instructions and removal of the obsolete game UI-size selector. Medium is the party-overlay baseline.
- Saved-access restoration retries temporary secure-storage failures. The update helper now confirms it started before Atlas closes.

## Reporting

Technical diagnostics include allowlisted hardware/display context and failure information. Closing session reports now send automatically by default while reporting is enabled; both controls remain in Settings → Privacy. Existing beta installs receive this default once; later opt-outs are remembered. Reports exclude access codes, player names, chat, screenshots, exact positions and routes.

## Beta testing notes

Tracking remains approximate; opening the game map can help correct drift. Named locations indicate possible spawns, not live enemy presence. Dungeon entry/exit, fullscreen overlays, resolution changes, border transitions and respawn recovery still need wider live gameplay testing. Use Windowed Fullscreen/Borderless if exclusive fullscreen hides the overlay. Testers should check the new stamina-bar heading against their game HUD.

Please report Atlas version, display resolution/scaling, what happened and steps to reproduce in Discord's bug-reports channel.
