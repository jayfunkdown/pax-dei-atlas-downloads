# Pax Dei Atlas 0.927 Beta

22 October 2026

A beta reliability and readability update for invited Windows 10/11 x64 testers.

[Download the Windows installer](https://github.com/jayfunkdown/pax-dei-atlas-downloads/releases/download/v0.9.27/Pax-Dei-Atlas-Setup-0.9.27-x64.exe) · [Tester instructions](https://github.com/jayfunkdown/pax-dei-atlas-downloads/blob/main/BETA-TESTING.md)

## Install or update

Existing testers: use **Settings → Updates**, or close Atlas and run the official Setup over your existing installation. No uninstall is needed. Saved access, settings, pins and watches are retained. This is a required pre-1.0 beta update when offered through the beta updater.

New testers: run Setup and enter your privately supplied beta access code. Log into Pax Dei and open the game map with your player arrow visible to establish position. Keep codes private. Discord is optional for downloading and using Atlas. This beta installer is not Windows publisher-signed; use the official download above.

## Tracking recovery

- Same-area home ports now recognize the game's loading-screen signal even when the province and area names do not change. Atlas clears the old position anchor and requests fresh landmark evidence instead of rejecting the destination as impossible movement.
- Respawn/revive signals invalidate stale positions, including near PvP gates. Fresh post-load coordinates and area evidence take priority over old estimates.
- Nearby walking border handoffs retain an estimate only when fresh movement, destination and HUD evidence agree. In-game area-reading gaps keep the map visible rather than showing the black login cover.
- Recovery checks reject stale results and preserve newer game-map confirmations. Local diagnostics record recovery timings and causes without screenshots or exact positions.

## Filters and favourites

- Add more than four favourites. All appear on the main map; the first four appear on the minimap.
- Main-map favourites fit the available height and scroll when needed.
- Escape closes Filters, including while typing in its search box.
- Favourite changes save immediately, and valid favourites restore independently of unrelated outdated settings.
- The Filters search field now uses a readable parchment background with a dark outline.

## Readability and search pins

- Smaller current-location text, larger branding and online/offline counts, and larger market quantities/prices improve readability.
- Tracked-item names match the market-list names in size and weight, with larger detail text underneath.
- Relic and market pins show in their own search tab. On Party, only pins with Route enabled are shown. Empty searches keep the map clear; selecting a listed result reveals its marker.
- Majestic relics consistently display Tier 4.

## Map-data corrections

- Resolved reviewed source records and corrected dungeon associations; an unassigned garlic record was dropped rather than placed on an unknown map.
- Matching named wolf encounters are attached to their closest reviewed wolf cave across the maps. Original source coordinates and earlier explicit corrections are preserved; unrelated enemies remain in their existing areas.

## Known beta limits and feedback

Tracking remains approximate. The latest home-port fix passes automated lifecycle tests, but another live same-area home-port, loading-border and respawn test is still outstanding. This release does not claim every tracking delay is fixed. If recovery stalls, opening the game map with a clear player arrow remains a manual recovery option. There is no indoor position tracking.

Market data updates hourly and may include sold stock. Named encounters indicate possible spawns, not live presence. For bugs, include the time, Atlas version, departure/destination, whether you walked or ported, whether loading appeared, and whether M corrected it. Remove access codes, private room codes and unrelated chat from screenshots.
