# House Mardenholt — Atlas 2.0 preview

Status: **review branch, not published to the live Visitor Site**

## Approved visual direction
- House Mardenholt heraldic crest **and** wax seal.
- Elegant noble-cartography with a weathered traveller's-map finish.
- Major location labels appear on the map; smaller sites are revealed on selection.
- The design and explicitly recorded chapter visits ship together.

## Implemented
- Two independent hand-inked SVG continent illustrations (Eastern Kingdoms and Kalimdor), parchment and heraldic ornaments.
- Chapter-by-chapter progress slider; search, location categories, a keyboard-accessible map and a connected Keeper's Ledger.
- Direct chapter links, exact published dates and existing companion metadata.
- 58 confirmed places, 98 explicit chapter/place associations, across Chapters I–XVI.
- Relative placement of Riverglades east of the Badlands and Burning Steppes, and a separate Krol'dok Stronghold marker (not a verified entrance).
- Only previously published events appear in the atlas; passing location references in the prose do not create a visit.
- No chapter text, illustration selection, companions, or editor files are changed.

## Important geographic qualification
Hand-illustrated placements are **interpretive**, not pixel-accurate coordinates extracted from WoW Forever client files. Dungeon entrances and exact zone boundaries should not be asserted from the decorative map. This is a historical journey visualization, not a navigation addon.

## Review checklist
1. Confirm the two continent silhouettes and heraldic styling match the desired v2.7 feel.
2. Check important marker placement on desktop and mobile.
3. Click Riverglades, Krol'dok Stronghold, Booty Bay, Gadgetzan, and Theramore, and follow links into the 16 existing chapters.
4. Test search, location filters, continent tabs, keyboard access, and Chapter I–XVI progress slider.
5. Confirm no previously approved chapter/gallery changed.
6. Only after approval, merge this feature branch into `main`.

## Files
- `atlas.html` — standalone preview UI with an embedded read-only ledger snapshot.
- `data/atlas-journeys.json` — explicit, inspectable travel ledger.
- `docs/ATLAS-V2-PREVIEW.md` — this specification.

Reference for Riverglades' general placement: Warcraft Wiki's Riverglades zone description, east of the Badlands and Burning Steppes.
