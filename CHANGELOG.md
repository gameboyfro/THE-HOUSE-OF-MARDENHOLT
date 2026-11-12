# House Mardenholt — CHANGELOG

Each change records **version, date, Added, Changed, Fixed, Removed, Pending**, and affected files. Only actual completed changes belong under Added/Changed/Fixed/Removed.

## [v2.3.1] — 2026-11-12 — Chapter VI illustrated plates
### Added
- Six finished aged-parchment, painterly journal illustrations for Chapter VI: two Darkmoon Faire scenes, Naralex in Wailing Caverns, Atte and dual-sword Thundrus fighting Big Will at Fray Island, and two views of the Dun Morogh snowstorm.
- Captions and image references in the Chapter VI visitor reader.

### Changed
- README acknowledges that Chapter VI's illustrations are now published.

### Fixed
- The published Chapter VI no longer shows a missing-illustration placeholder.

### Removed
- Nothing. Previously approved portraits, Atlas layout, and Chapters I–V remain unchanged.

### Pending
- Chapters VII and VIII are not yet published; companion biographies await players' contributions.

**Files affected:** `assets/chapter-06-plate-01.webp` through `assets/chapter-06-plate-06.webp`, `chapters.js`, `README.md`, `CHANGELOG.md`.

## [v2.3.0] — 2026-11-12 — Chapter VI published
### Added
- Chapter VI — Of Broken Chains and Distant Shores (9 November 2026), in Atte's first-person voice, including Darkmoon Faire, five cleared dungeons and their 31 named encounters, Fray Island, the Sleeping Bag clue trail, the Dun Morogh blizzard and a final night in Ironforge.
- Confirmed Chapter VI encounter summaries for Furrassic Maul and Thundrus Cheeklapper. Melan Holya's existing Chapter VI encounter is now attached to a published chapter.

### Changed
- Chapter VI location records are now classified as visits documented in a published chapter.
- README's chapter and companion counts have been brought up to date.

### Fixed
- The visitor reader, Timeline, Atlas and Companions Ledger now have a published Chapter VI to link to.

### Removed
- Nothing. Chapters I–V and approved companion portraits remain unchanged.

### Pending
- Six illustrated Chapter VI plates have been prepared separately but are not yet deployed to GitHub Pages. Chapter VI currently displays its prose without illustrations; do not claim the artwork is published.
- Chapters VII and VIII remain unpublished; family history proposals remain on hold.

**Files affected:** `chapters.js`, `data/companions.json`, `data/locations.json`, `README.md`, `CHANGELOG.md`.

## [v2.2.0] — 2026-11-12 — Melan Holya and Chapter VI field-note destinations
### Added
- Melan Holya joins the Companions Ledger as a Human Priest, Initiate, with her approved portrait. Chapter VI encounter details are staged for when the chapter is published.
- Eleven missing location records from the actual 9 November journey, with dated notes about the visit, including The Stockade, Excavation Site: Wetlands, Wailing Caverns, Fray Island, Ratchet, Stonetalon Mountains, Gnomeregan, the Darkmoon Faire, the Barrens, Silverpine Forest and Dun Morogh.

### Changed
- Atlas entries and schematic pins distinguish visits confirmed by private field notes from visits documented in published Chronicle chapters.
- Five existing location records now include their 9 November field-note visits.
- README now reflects nine companions and five published chapters.

### Fixed
- Companion dossiers indicate when their first recorded adventure awaits publication instead of claiming no journey exists.

### Removed
- Nothing. Previously approved portraits, the Atlas layout and Chapters I–V remain unchanged.

### Pending
- Chapter VI's completed prose and illustrated plates are still private and not published; its encounter links become visible when the chapter is published.
- Further companion biographies await player contributions.

**Files affected:** `assets/crew-2026/melan-holya.webp`, `data/companions.json`, `companions.html`, `data/locations.json`, `atlas.html`, `README.md`, `CHANGELOG.md`.

## [v2.1.0 — PREVIEW] — 2026-11-10 — Chapter V and companion encounters
### Added
- Chapter V in the confirmed order: Darkshore / Master's Glaive → Blackfathom Deeps → Duskwood → Wetlands → Stormwind.
- Approved Master's Glaive watercolor illustration attached as the Chapter V plate.
- Three Kalimdor location records and Chapter V encounters for Quilby, Civa and Sumtingwong.

### Changed
- README reflects deployed visitor website and preview workflow.
- The existing public Atlas layout is preserved; the proposed illustrated Atlas redesign was rejected and removed from this release.

### Fixed
- Chapter I image caption spelling of Quilby.
- Stormwind and Stormwind City are unified in the public places statistic.
- "The Hall of Thanes" name is aligned with the location record without changing the map layout.

### Removed
- Proposed new Atlas background artwork from this preview; no previous artwork or journal material removed.

### Pending
- Browser/mobile visual QA and owner approval before live publication.
- Further Atlas redesign deferred; companion biographies and private editor changes remain separate.

**Files affected:** `chapters.js`, `data/locations.json`, `data/companions.json`, `atlas.html` (name correction only), `index.html`, `assets/chapter-05-plate-01.webp`, `README.md`, `CHANGELOG.md`.

## [v1.0.3] — 2026-11-07 — Published Visitor content uploaded (not live)
### Added
- `index.html` containing the three approved, published Chronicle chapters: 4, 5 and 6 November 2026.
- Seven Chronicle illustrations and fourteen House artwork images in `assets/`.
- `.nojekyll` for static GitHub Pages publishing.

### Changed
- Moved embedded image data out of the exported Visitor HTML into the corresponding image files for faster loading and manageable GitHub uploads.
- Updated README with accurate repository status and GitHub Pages instructions.
- **No changes to chapter text, artwork pixels, character descriptions, or the site's design.**

### Fixed
- Removed dependence on a single approximately 10 MB HTML file for deployment. Verified all local image references and JavaScript syntax; verified the uploaded `index.html` against the prepared source.

### Removed
- Nothing from the published stories or imagery.

### Pending
- GitHub Pages has **not** been enabled; the repository is **Private**. Public launch requires the owner's explicit decision and Pages configuration.
- Moderated notes beneath individual chapters.
- The Wanderer's Map linked to journal locations and activities.

**Files affected:** `index.html`, `assets/` (21 images), `.nojekyll`, `README.md`, `CHANGELOG.md`.

## [v1.0.2] — 2026-11-07 — Repository preparation (unpublished)
### Added
- Expanded repository README with safe publishing steps and project status.
- This version-by-version changelog on GitHub.

### Changed
- The README now distinguishes the **public Visitor edition** from the **private Editor** and describes versioning.

### Fixed
- Clarified that GitHub Pages has **not** been enabled and that an HTML entry file has **not** been uploaded.
- Clarified that the existing v1.0.1 Visitor template contains **zero published Chronicle chapters**.

### Removed
- Nothing.

### Pending
- Upload a verified, chapter-bearing published Visitor export as `index.html`.
- Configure GitHub Pages and confirm that the public site loads.
- Moderated visitor comments for each chapter (requires storage/moderation service).
- Chronicle-driven map of Azeroth and publisher integration.

**Files affected:** `README.md`, `CHANGELOG.md` (documentation only). No journal, images or HTML changed.

## [v1.0.1] — 2026-11-06 — Offline Visitor packaging
- **Added:** Clearly named Visitor file and `index.html` copy in downloadable package.
- **Changed:** Instructions for opening Visitor and exporting chapters from Editor.
- **Fixed:** Confusing Visitor-template filenames.
- **Removed:** None.
- **Pending:** No online deployment or embedded chapters in the packaged Visitor template.
- **Files:** Offline release ZIP only; not uploaded to GitHub.

## [v1.0.0] — 2026-11-06 — Version-history baseline
- **Added:** README, CHANGELOG, content-history document and file-version metadata in the offline package.
- **Changed:** Nothing in functional website source.
- **Fixed:** No new code fixes (Norwegian calendar had been fixed earlier).
- **Removed:** None.
- **Pending:** Hosting, comments, map and automated chapter versioning.

## Before version tracking
Earlier work includes illustrated Chronicle support, Norwegian calendar, artwork adjustments, site audit and Greybough Hall corrections. Exact dates and complete change diffs for these earlier iterations have **not** been independently reconstructed. Do not infer additional version numbers.

---
**Policy:** Do not overwrite approved art or privately stored journal content without express approval. Preserve backups and make changes in small, reviewed releases.
