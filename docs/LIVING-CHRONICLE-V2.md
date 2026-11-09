# House Mardenholt — The Living Chronicle v2.0

Development branch: `feature/living-chronicle-v2`. The live `main` branch remains unchanged until review.

## Confirmed scope
- Full Azeroth map, expandable for future continents and expansions; markers link to recorded chapters.
- Journey timeline: distinguish in-universe history from actual gameplay dates.
- Full companion dossiers, with portraits and approved biographies, linked to chapter appearances.
- Preserve existing index.html, chapters.js, illustration assets, private local editor, and one-click publishing.

## Data contracts
Use immutable IDs for chapters, locations, companions, events, and comments. Chapter titles are display text, not relational keys. A chapter can reference many locations, events, and companions. All published records must exclude private drafts.

Suggested public files:
- `data/locations.json`: `{version:2,locations:[{id,continent,zone,name,mapX,mapY,chapterIds}]}`
- `data/companions.json`: `{version:2,companions:[{id,name,race,class,portrait,biography,chapterIds,approvedLore}]}`
- `data/events.json`: `{version:2,events:[{id,chapterId,title,calendar,date,locationId,description}]}`

## Migration and safety
1. Snapshot current `main` and export local editor JSON before migration.
2. Read existing `chapters.js` without mutating the three published chapters.
3. Assign stable IDs; preserve chapter ordering, text, and illustration references.
4. Add public components behind feature flags. No existing chapter reader regressions.
5. Implement the editor's corresponding management screens and GitHub publishing revision checks.
6. Verify desktop/mobile, editor round-trip, private draft exclusion, and rollback before merge.

## Out of scope
Public comments, moderation services, external databases, and visitor submissions are excluded by project decision. The site remains static on GitHub Pages.

## Story canon
Only record actual gameplay as factual adventures. Keep Warcraft canon distinct from invented House Mardenholt lore; get companion owners' approval before asserting biographical details.
