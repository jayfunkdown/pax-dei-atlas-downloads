# Pax Dei Atlas feature guide

Atlas is a Windows map companion for Pax Dei. This guide shows the current beta interface. Screenshots use a fictional party and sample values; the interface and behavior may change during development. An invited-testers beta is now available; see [Beta testing](BETA-TESTING.md) for downloads and setup.

[Back to the project overview](README.md)

## Main map and position tracking

The main map opens around your current area. Drag the parchment to pan, use the mouse wheel or the plus/minus controls to zoom, and choose another province from the selector below the map. Recenter returns to your current area. Crossing an area boundary keeps your chosen zoom. Small position corrections can move the marker without constantly moving the whole camera.

Atlas uses visible game-map and compass information, then estimates movement between position confirmations. Tracking accuracy can vary, especially after interruptions or when landmarks are unclear. During a brief unreadable compass interval, Atlas can keep estimating movement from the last heading for up to eight seconds; a longer outage pauses movement until a fresh heading arrives. Turns during that interval can reduce accuracy. If the marker needs correcting, opening the in-game map with the player arrow visible can help Atlas confirm its position. Panning the game map to scenery without a player arrow should not become a position fix.

![Main map and adjustable map/party divider](screenshots/main-map.png)

## Minimap

The circular minimap provides a compact view while you play. Its controls include zoom, movement, route tracing, named-encounter notifications, settings and hiding the minimap. Party members outside the visible area have direction indicators near the edge.

The minimap can be shown or hidden independently of the main window. Close the main window when you want to quit Atlas.

![Circular minimap, favourites and map controls](screenshots/minimap.png)

## Map filters and pinned favourites

Choose the locations, resources, creatures and other map categories you want to see. Search for a particular entry, expand a category, or turn a group on or off. The filter panel opens over the map, leaving the map layout in place.

Pin up to four favourites to make frequently used filters accessible on both maps. For example, keep a useful resource type nearby without reopening the full filter list each time.

![Filter panel and searchable map categories](screenshots/filters.png)

## Flags and the route trace

Use **Alt + left-click** on the map to add, replace or remove your flag. Party flags are shared so the group can agree on a destination; an off-screen flag retains a direction indicator.

Turn **Trace** on to show your recent route as a clear gold line with a dark outline. Small corrections can remain connected, while large position jumps start a separate section instead of drawing a long line across the map. The trail is temporary: disabling it clears it, and it starts fresh in a new app session. It is a route display, not an automatically calculated walking path.

The main-map screenshot above includes an example flag and route trace.

## Party travel and the movable divider

Create a room or join with a shared room code. The party panel shows travellers, their areas and approximate distances when their positions are available. Party markers and names also appear on the map.

Drag the divider between the map and the party panel to give either section more space. Make the map shorter to see more party members, or give it more of the window when you want to concentrate on navigation. Scrolling remains available when a section needs it.

Treat a real room code as an invitation to your group. The example below uses a fictional room rather than a live one.

![Sample party roster with areas and distances](screenshots/party.png)

## Roll and Pass

Start a roll from the action bar, or pass when you do not want to participate. Illustrated cards reveal each result. When the round finishes, the winning card rises and displays a **Winner** label. The group can see both rolls and passes together.

![Sample roll results, a winner and a pass card](screenshots/roll-and-pass.png)

## Ready checks

Start a ready check before the group moves or begins an activity. Each traveller has a card showing **Ready** or **Not ready**, making it clear who is still outstanding. The pending check includes a countdown; once everyone is ready, the group sees **All ready**.

![Three travellers ready, with one still outstanding](screenshots/ready-waiting.png)

![Completed ready check with all travellers ready](screenshots/all-ready.png)

## Wait requests

Use **Wait** to ask the party to pause briefly. The request appears as a short notification with the requesting traveller's name. Party presentations are queued so competing requests and card sequences can be shown in order.

![A fictional traveller's wait request](screenshots/wait-request.png)

## Named enemies, relics and crafting results

When you approach a supported possible encounter, Atlas can display an illustrated set of cards: the named enemy, its special relic and a related crafting result. These describe known relationships; they do not detect whether that enemy is alive.

![Named enemy, relic and related equipment cards](screenshots/named-enemy-cards.png)

Mapped POIs trigger from about **65 metres** away; unmatched standalone locations use **90 metres**. Nearby enemies share their POI’s complete card sequence. New POI card groups queue after the current group. Surface discoveries retain their circle highlight and larger brass encounter-card replay icon for **15 minutes**. Click to replay the whole group; replay does not extend expiry, and walking away/back does not automatically repeat it during that window. Several discoveries can remain visible. After expiry, the next approach can trigger again.

Only one nearby dotted guide appears. Clicking replay selects that encounter; a newly triggered encounter takes over. Ordinary POI guide lines disconnect beyond **100 metres**, while the replay marker remains for its full window. Named cards sit at the game viewport’s bottom centre, scale with resolution, and use an opaque heading at the Medium stamina-bar position. Surface cards no longer black out the minimap. Use Named to turn the feature off.

Some supported enemies have broader open-ground spawn zones, including reviewed areas in southwest Kerys. Those remain area highlights because a single tower marker would misrepresent their records. Several possible spawn locations do not mean that every displayed enemy can spawn at every point inside a combined area.

![A local named-location highlight on the main map](screenshots/named-location.png)

## Dungeon maps and encounter references

Supported dungeon pages provide map artwork and a reference to possible named enemies, relics and crafting results. Atlas displays a dungeon notice and pauses position tracking inside the dungeon; it does not claim to show your live position on the dungeon map. The overworld view returns after fresh position evidence. Approaching an entrance only highlights it: cards wait for the interior Zone / Biome tag, play once on entry, and cannot be replayed.

![Dungeon map and encounter-reference interface](screenshots/dungeon-map.png)

## Minimap appearance and HUD alignment

Choose a minimap size and adjust opacity. Party overlays use the Medium game-UI baseline; named cards scale with resolution and stay at the viewport bottom. Use **Reset overlay position** if the placement needs restoring. The minimap is circular.

![Minimap appearance and HUD alignment settings](screenshots/settings-minimap.png)

## Sound and shortcuts

The sound setting controls Atlas effects such as roll winners, ready checks and named-enemy drums. Set the volume to zero to mute them.

![Effects volume control](screenshots/settings-sound.png)

The default shortcuts are **Alt + M** to show or hide the minimap, **Alt + I** to zoom in and **Alt + O** to zoom out. Click a binding in Settings to change it. If another application already uses a shortcut, choose a different binding or retry registration.

![Configurable shortcuts](screenshots/settings-hotkeys.png)

## Beta access and saved sign-in

An authorized beta access code unlocks Atlas. The app asks for the code, not an email address. Valid saved access is checked when the app opens; returning users should not see the unlock form during that check. The form is shown when access is missing, expired or cancelled.

Online checks keep beta access revocable. Brief connection interruptions are allowed. A longer interruption can pause access, but the saved session is retained and can resume automatically when the connection returns. Updating the app keeps that saved session in the existing profile.

![Code-only beta unlock screen](screenshots/beta-access.png)

## Online/offline status

The top of the main window shows online and offline beta-access totals. These count valid access keys, not necessarily distinct people. A key with a recently verified active session is online; a valid key without one is offline. Names and access codes are not listed in these totals. The values in the screenshots are examples.

## Updates

Settings includes a manual update check. Packaged beta builds also check automatically after opening and periodically while running. When an approved newer version is published, the main map and minimap can display an update notice.

Click **Update now** to download the approved installer from the dedicated GitHub downloads repository. Atlas verifies the download before handing it to the installer, closes, installs into its existing folder and reopens. Settings and valid saved access remain in place.

The app reports that it is current when the installed version matches the published beta. This screenshot shows that state:

![Updates settings with no offered public release](screenshots/settings-updates.png)

The next image illustrates how an offered update will look. It is a screenshot fixture illustrating the offer shown when a newer version is available:

![Illustration of the update-available screen](screenshots/update-available.png)

## About and feedback

Atlas is a fan-made companion in active development. Feedback, ideas and reproducible bug reports are welcome on the [Atlas Discord](https://discord.gg/YjJxCBbeJU) and through this repository's Issues page. Discord has general chat, release notes, bug reports, feature requests and feedback. A website is planned.

![About screen](screenshots/about.png)

Please do not include real beta codes, private room codes, personal information or unrelated player chat in public reports. Atlas is unofficial and is not affiliated with or endorsed by Mainframe Industries.

## Beta 0.91 encounter presentation
Named-card borders follow the crafted item's tier: II keeps a simple brass border, III uses sculpted corner detail, and IV adds raised ornaments. Every enemy card set uses the same drum cue and a 10-second hold between two-second fades.

![Tier II, III and IV cards from the beta renderer](screenshots/named-card-tiers.png)

POI notifications use65m entry/100m exit. Standalone encounters use90m entry/100m exit with a larger180m-wide highlight. New POI highlights replace older ones immediately; already playing card groups finish before the next queued group.

Dungeon recognition currently estimates entry after60 seconds within30m of a documented entrance. The main window shows the dungeon reference map and roster; the minimap shows dungeon status. Indoor position tracking is unavailable. Detection can trigger while waiting outside and currently depends on Named being enabled.

## Optional beta statistics

Settings → Privacy controls usage and reliability reporting, enabled by default for beta testing. Reports use a random installation identifier, are stored privately for up to 90 days, and exclude names, access codes, chat, screenshots, exact positions and routes. See the [tester guide](BETA-TESTING.md#beta-statistics-and-privacy) for details.

## Relic Search and Market

The lower panel has Party, Relic Search and Market tabs. Search and results are on the left; pins and market watches are on the right. Relic Search finds relics and their crafted items, with tiers shown on pinned relics. Search is scoped to the selected main-map province; when there are no local matches, other-province matches can be shown or pinned directly.

Market detects your game server and shows listings for the selected province, including item icons, quantity available, normal-stack price and listing total. Hovering a result highlights its stall. Market data is supplied by gaming.tools and updates hourly; listings may have sold since the last update. World-wide watches check all provinces on your server for an item, optionally below a maximum normal-stack price. New matching listings appear in the tracked list with pin controls and a Market-tab notification. Checks run while Atlas is open.

You can keep multiple relic and market pins, each with an independent Route checkbox. Pins remain until manually removed. Green relic and blue market dotted guides use the appropriate gates for another province. Named encounter replay icons take visual priority at the same POI without deleting a relic pin. These are straight direction guides, not navigable road routes.
