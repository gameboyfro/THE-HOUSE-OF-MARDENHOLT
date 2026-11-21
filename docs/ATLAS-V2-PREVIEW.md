# House Mardenholt — The Wanderer's Atlas 2.0: placement and heraldic-color audit

**Status:** Unpublished preview on `feature/mardenholt-atlas-v2-preview`. The public `main` branch, 16 chapters, and all existing illustrations are unchanged.

## Owner-approved decisions

1. Exact WoW Forever geography is more important than decorative placement; reference `https://wowforevermap.com/`, and use actual client-derived map data where available.
2. Place dungeon markers at the known instance entrance or published dungeon marker. If the precise portal has not been established, anchor the named zone or known location and disclose the limitation.
3. Five distinct categories: **capitals** (royal gold `#b89240`), **dungeons** (crimson `#a23f39`), **towns and settlements** (teal `#32786f`), **regions** (forest green `#577445`), **landmarks** (violet `#7e6599`).
4. **Regions are hidden by default** and shown through the Regions filter, or if directly searched for.
5. **Labels stay dark parchment ink**; only the marker symbols use category colors.
6. Only places confirmed visited in published chapters appear. Darnassus remains absent until the Chronicle records a visit.
7. Audit all 16 chapters and their recorded locations across both continents.

## Exact geographic projection

The former hand-drawn silhouettes and unsupported third-party image links have been replaced with the two genuine WoW Forever continent maps, bundled as `assets/atlas/forever-eastern-kingdoms.jpg` and `assets/atlas/forever-kalimdor.jpg`. Their source is the publicly available game-client map atlas maintained by `peligwen/peligaming`, build **1.60.1.69913** (exported 2026-09-22). They remain artwork copyrighted by Blizzard Entertainment. This is a non-commercial fan website; attribution appears on the map.

The published map dataset includes the native `UiMap` rectangle for each continent:

- Kalimdor: `[-186.28,45.21,635.39,592.99]` (client map 1414)
- Eastern Kingdoms: `[372.23,54.44,1161.45,580.58]` (client map 1415)

The displayed map SVG and the map image are **the same 1002 × 668 coordinate system**. Every marker is projected using these rectangles, never by guessing where its place is on the background:

```js
x = (worldX - continentLeft) / (continentRight - continentLeft) * 1002;
y = (worldY - continentTop) / (continentBottom - continentTop) * 668;
```

Exact source-world positions (`worldX`, `worldY`), source type (`positionSource`) and precision (`positionPrecision`) are retained for every location in `data/atlas-journeys.json`. Markers never lose their original anchor; where two locations overlap visually, a short tether connects the icon to the precise geographic dot.

## Visit and precision audit

- **58 confirmed locations** linked to 98 chapter visits.
- Eastern Kingdoms: 39 entries.
- Kalimdor: 19 entries.
- **13 named city/town/flight-point markers** from game data.
- **10 classic instance markers** from game data.
- **9 named subzones**, including Krol'dok Stronghold (not a confirmed portal point).
- **21 geographic zone centres**, intentionally not presented as exact entrances.

### Entrance / temporary-location exceptions still requiring in-game proof

These markers are geographically anchored, but must not be presented as exact instance portals:

| Location | What is known | What is not yet proved |
|---|---|---|
| The Hall of Thanes | Beneath Old Ironforge; marked at Ironforge | Exact portal coordinates conflict across published guides |
| City of Dalaran | Dungeon in Dalaran, Alterac Mountains | Exact sewer entrance location not independently verified |
| Darkmoon Faire | Fair area represented by Goldshire | Specific event tent position may vary |
| Excavation Site: Wetlands | Near Whelgar's Excavation Site / Thelgen Rock; marked at guide-estimated location | Sources disagree on exact portal; await direct in-game verification |
| The Drowned City | Community-reported entrance around Stranglethorn Vale 21,28 near the Vile Reef, underwater | Direct player confirmation pending |

The named Krol'dok Stronghold subzone is derived from the client's map geometry, but the **dungeon portal** is not separately identified. Its pin is a subzone marker, not a claimed portal.

## QA checks completed

- Reconstructed the 58 entries from one explicit travel ledger, not text-search heuristics.
- All 58 projected coordinates are inside the 1002×668 continent-map bounds.
- Verified the original images' Git blob SHAs match the imported files.
- Tested navigation logic with a simulated document: 26 visible non-region markers on Eastern Kingdoms, 11 on Kalimdor, region-filter visibility, and targeted search for Gadgetzan.
- Checked JavaScript compilation and all category color assignments.
- Change scope remains `atlas.html`, `data/atlas-journeys.json`, this document and the two new continent map images, only on the preview branch.
- Visual approval by the site owner remains required before the branch can be merged.

## Sources

- WoW Forever Map for current Forever zones and community marker warnings: https://wowforevermap.com/
- Game-client map art, geometric projection data, classic instance markers, named subzones, town markers and taxi nodes: https://github.com/peligwen/peligaming
- Original data file: https://github.com/peligwen/peligaming/blob/main/public/tools/wow-forever/data/world-map/world-map.json
- The Drowned City entrance guide: https://mobalytics.gg/wow-forever/dungeons/drowned-city-complete-dungeon-guide-uncas
- Wetlands dungeon geographic guides: https://wowbocho.com/forever/dungeon/excavation-site/ and https://www.warcrafttavern.com/forever/guides/excavation-site-wetlands/
- Hall of Thanes guide: https://wowbocho.com/forever/dungeon/hall-of-thanes/
- World of Warcraft game map artwork © Blizzard Entertainment; assembled by `peligwen/peligaming` for a non-commercial fan map.

**Do not publish before approval.**
