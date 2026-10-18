# Pax Dei Atlas 0.924 Beta

A regular beta release for invited Windows 10/11 x64 testers.

[Download the Windows installer](https://github.com/jayfunkdown/pax-dei-atlas-downloads/releases/download/v0.9.24/Pax-Dei-Atlas-Setup-0.9.24-x64.exe) · [Installation and beta guide](https://github.com/jayfunkdown/pax-dei-atlas-downloads/blob/main/BETA-TESTING.md) · [Discord](https://discord.gg/YjJxCBbeJU)

## Install or update

Existing testers: use Atlas → Settings → Updates, or close Atlas and run the official Setup over your current installation. Settings, pins, watches and valid saved access are retained; no uninstall is needed. This is a regular required pre-1.0 beta update. Older clients whose update helper closes without installing can run Setup manually.

New testers: download and run Setup, open Atlas, then enter the beta access code supplied privately by the project owner. Access codes remain valid until revoked. Never post them in Discord. Log into Pax Dei and open the in-game map with your player arrow visible to establish position.

## Relic Search

- New Party, Relic Search and Market tabs in the lower panel, with an even two-column layout and larger, more readable text.
- Search relics or their crafted items with styled autocomplete and live result filtering. Relic pins show the crafted items and tiers.
- Results follow the main-map province. If nothing matches there, see where matches exist and either show them on that map or pin them without switching maps.
- Keep multiple relic pins. Each Route checkbox independently shows or hides its green directional guide. Pins stay until manually removed, including after arrival or encounter playback.
- Multiple relics at the same POI share one map symbol. Named encounter replay icons take visual priority there without deleting your pin.

## Market and item watches

- Market detects your game server and displays listings for the province selected on the main map. Searching filters both the list and stall markers; hovering highlights the stall.
- Search results, other-province results and tracked matches share item icons and Qty, Stack and Total columns. Stack is the price for the item's normal full stack; Total is the cost of all quantity in that listing.
- Pin multiple market destinations, with independent blue Route guides. Touching market symbols merge at the current zoom.
- Watch an item across every province on your server, even when none are currently for sale. Optional price limits use gold per normal stack.
- New matching listings add a Market-tab notification and show their province, quantity and prices. Show a match on the map or pin it directly. Watches persist between launches.
- Relic and market routes use the connecting gates when their destination is on another province. They remain independent of the named encounter guide.

## Named encounters and map data

- Playing encounters slowly pulse their replay icons. Card fade-in is 0.5 seconds, and the existing heading is adjusted slightly to cover the stamina-bar area.
- The named dotted guide stays on the last clicked or newly triggered encounter, rather than disappearing when approaching another highlighted area.
- Fixed packaged named-card illustrations that could appear as unavailable.
- Refreshed upstream map markers while preserving reviewed named locations. Resources and ordinary NPCs display individually; harvesters remain ordinary NPCs.
- Named boundary checks now cover all named enemies on map-data refreshes, expanding or creating triggerable groups for uncovered locations while retaining curated locations.

## Usability and access

- Fixed the gold player arrow being obscured by POI/replay/search icons. It now renders above map symbols without blocking their clicks.
- Recenter beside Filters restores your current location at the normal area zoom. Returning to Party does the same.
- The map selector is below the map on the right. The top controls stay on one row in narrower windows.
- The map divider has a useful minimum map height and stays clear of the bottom frame.
- Clear pushpin controls, aligned numeric/Pin columns, scrollbar spacing and larger remove buttons. Relic and market guides use softer green and blue dots.
- Additional saved-access recovery and session visibility fixes. Existing valid access is retained when updating.

## Beta testing notes

Tracking still uses visible game information and remains approximate; it is not a new direct game-position feed. Reopen the game map with your player arrow visible if the marker drifts. Named locations indicate possible spawns, not live enemy presence. Dungeon, border, respawn and display-resolution behavior still needs wider gameplay feedback.

Market data comes from gaming.tools' hourly snapshots, not instant game events. Listings may already have sold. Watch checks run while Atlas is open; a delayed provider request can delay results. Gates provide straight direction guides rather than pathfinding. Item images need an internet connection.

The installer is not Windows publisher-signed yet; use the official download above. Beta access remains private. Please report the Atlas version, display resolution/scaling, what happened and steps to reproduce in Discord's bug-reports channel. Include screenshots where useful, with private codes and unrelated chat removed.
