# House Mardenholt — CHANGELOG

Each change records **version, date, Added, Changed, Fixed, Removed, Pending**, and affected files. Only actual completed changes belong under Added/Changed/Fixed/Removed.

## [v2.1.0 — PREVIEW] — 2026-11-10 — Chapter V and Atlas
### Added
- Chapter V in the correct travel order: Darkshore / Master's Glaive → Blackfathom Deeps → Duskwood → Wetlands → Stormwind.
- Three new Kalimdor location records and Chapter V encounters for Quilby, Civa and Sumtingwong.
- Original parchment atlas image and clickable location markers across both continents.

### Changed
- Atlas now presents the illustrated two-continent map; marker placements remain approximate.
- README now reflects the current deployed visitor website and preview-release workflow.

### Fixed
- Chapter I illustration caption now spells Quilby correctly.
- Stormwind and Stormwind City are no longer counted separately in the public places statistic.
- Hall of Thanes Atlas name matches the recorded location.

### Removed
- Nothing from previous chapters or approved companion artworks.

### Pending
- Attach the approved Master's Glaive Chapter V illustration as a website image asset before live publication.
- Browser/mobile visual QA and owner approval of this preview.
- Companion biographies and private editor follow-up remain separate tasks.

**Files affected:** `chapters.js`, `data/locations.json`, `data/companions.json`, `atlas.html`, `index.html`, `assets/azeroth-parchment-atlas.webp`, `README.md`, `CHANGELOG.md`.

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
