# House Mardenholt — Atlas 2.0 preview

Status: **review branch, not published to the live Visitor Site**

## Approved visual direction
- House Mardenholt heraldic crest **and** wax seal.
- Elegant noble-cartography with a weathered traveller's-map finish.
- Major location labels appear on the map; smaller sites are revealed on selection.
- The design and explicitly recorded chapter visits ship together.

## Implemented
- Correct World of Warcraft: Forever continent map artwork (Eastern Kingdoms and Kalimdor), with House Mardenholt parchment framing, crest and seal. Map art remains © Blizzard Entertainment and is loaded from Forever Atlas as a temporary external image for this preview.
- All confirmed markers rendered **on top of the geography**, not beside it: heraldic symbols, major location names, overlap adjustments and map zoom. Chapter-by-chapter progress slider; search, location categories, keyboard-selectable marks and a connected Keeper's Ledger.
- Direct chapter links, exact published dates and existing companion metadata.
- 58 confirmed places, 98 explicit chapter/place associations, across Chapters I–XVI.
- Riverglades is marked east of the Badlands and Burning Steppes, with a separate Krol'dok Stronghold marker in the region. WoW Forever's official map shapes replace the invented continent silhouettes.
- Only previously published events appear in the atlas; passing location references in the prose do not create a visit.
- No chapter text, illustration selection, companions, or editor files are changed.

## Important geographic qualification
The **map geometry is taken from WoW Forever continent artwork**, not invented coastline drawings. Pin positions are manually aligned on the image, with near-neighbor spacing to prevent collisions; they are not yet client-derived exact in-game coordinates, especially for some dungeons. Exact dungeon portals should not be inferred from their icons. The displayed map references external artwork, which should be reviewed before permanent hosting. This is a historical journey visualization, not a navigation addon.

## Review checklist
1. Confirm that the two real Forever continent maps render, are geographically recognizable, and retain the desired heraldic journal feel.
2. Check that every visible marker is over its region (not in sea or outside the map), inspect major labels on desktop and mobile, and test the zoom controls.
3. Click Riverglades, Krol'dok Stronghold, Booty Bay, Gadgetzan, and Theramore, and follow links into the 16 existing chapters.
4. Test search, location filters, continent tabs, keyboard access, and Chapter I–XVI progress slider.
5. Confirm no previously approved chapter/gallery changed.
6. Only after approval, merge this feature branch into `main`.

## Files
- `atlas.html` — standalone preview UI with an embedded read-only ledger snapshot.
- `data/atlas-journeys.json` — explicit, inspectable travel ledger.
- `docs/ATLAS-V2-PREVIEW.md` — this specification.

Reference for Riverglades' general placement: Warcraft Wiki's Riverglades zone description, east of the Badlands and Burning Steppes.

## Geographic and art references
- WoW Forever Eastern Kingdoms map: https://wowforeveratlas.com/media/forever-maps/eastern-kingdoms.webp
- WoW Forever Kalimdor map: https://wowforeveratlas.com/media/forever-maps/kalimdor.webp
- Forever Atlas index and art credit: https://wowforeveratlas.com/world (continent map artwork © Blizzard Entertainment)
- Riverglades geography: https://www.wowhead.com/forever/guide/riverglades-zone-overview and https://warcraft.wiki.gg/wiki/Riverglades
- Krol'dok location: https://www.wowhead.com/forever/guide/kroldok-stronghold-dungeon-overview-location-rewards
