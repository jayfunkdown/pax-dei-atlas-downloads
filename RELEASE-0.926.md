# Pax Dei Atlas 0.926 Beta

20 October 2026

A beta update for invited Windows 10/11 x64 testers, focused on reliability, performance and clearer search results.

[Download the Windows installer](https://github.com/jayfunkdown/pax-dei-atlas-downloads/releases/download/v0.9.26/Pax-Dei-Atlas-Setup-0.9.26-x64.exe) · [Tester guide](BETA-TESTING.md) · [Discord](https://discord.gg/YjJxCBbeJU)

## Install or update

Existing testers: use **Settings → Updates**, or close Atlas and run the official Setup over your current installation. Settings, pins, watches and valid saved access are retained; no uninstall is needed. If an older beta closes without completing its update, run Setup manually and reopen Atlas.

New testers: run Setup, launch Atlas and enter the beta access code supplied privately. Log into Pax Dei and open its map with your player arrow visible to establish position. Beta access codes remain valid until revoked. Keep them private. Discord is optional for downloading and using Atlas.

The installer installs for your Windows account without administrator access. This beta is not Windows publisher-signed yet, so Windows may show an unknown-publisher or reputation prompt. Use the official download above.

## Market search across all maps

- Searching now includes every map on your detected server, even when matches exist on the current map. Current-map results appear first, followed by other maps.
- Show a result on its map or pin it directly without switching the map you are viewing.
- Offers for the same item at the same stall combine into one row when their item quality and normal stack size match. Quantity and actual total cost are added together; Stack shows a price range if the stock has different prices.
- Tracked matches use the same layout and grouping after applying your price limit. Source orders still determine which stock qualifies.
- Item icons and Qty, Stack and Total columns remain consistent across map groups and tracked matches.

![Combined stock and one selected stall; renderer preview before the heading rearrangement](screenshots/market-stall-stock-0.926.png)

## Clearer map selection and location heading

- An empty relic or market search keeps result icons hidden. Clicking a listed result reveals just that destination; hovering alone does not populate the map.
- Typing a search shows its matching locations on the currently viewed map. Saved pins remain available independently.
- The ornate gold current-location heading now sits above the map frame, aligned left on one line. Its fade remains, and viewing another map is labelled **Viewing map:**.

![Current-location heading above the frame](screenshots/current-location-0.926.png)

## Reliability and performance

- Improved recovery after travel through PvP gates and between home valleys and Wildlands. Fresh arrival evidence takes priority over older area readings that could leave the marker at a border.
- Improved tracking-reader startup and recovery, with bounded background work and clearer local recovery diagnostics.
- Reduced repeated work in large marker groups, search results and tracked-item lists; auxiliary windows load less application code initially.
- Strengthened map refreshes, failed-load retries, update-download handling and saved-access recovery across the runtime upgrade.
- Hardened desktop permissions and handling of stale background results.
- Improved party connection cleanup and reduced repeated position traffic in larger groups.

## Known beta limits and feedback

Tracking is approximate. Portal and landmark recovery still need continued live testing across travel routes and game conditions; this update does not guarantee that all drift or pauses are resolved. Opening the game map with a clear player arrow can help confirm your position. There is no indoor position tracking.

Market snapshots update hourly and can include already-sold listings. Named locations describe possible spawns, not live enemy presence. Screenshots use fictional party details and example stock/prices.

For tracking reports, include the approximate time, departure and arrival areas, whether you ported or walked, and whether opening the game map corrected it. Include Atlas version, Windows resolution/display scale and game UI preset. Remove access codes, private room codes and unrelated chat from screenshots. Use [GitHub Issues](https://github.com/jayfunkdown/pax-dei-atlas-downloads/issues), Discord, or send the report through your beta contact.
