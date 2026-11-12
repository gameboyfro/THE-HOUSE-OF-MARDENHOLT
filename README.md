# THE HOUSE OF MARDENHOLT
**House Mardenholt — The Guardian Oak**  
*The Wanderer's Chronicle: the recorded adventures of Ser Atte Mardenholt in World of Warcraft: Forever.*

## Status
- **Website:** GitHub Pages visitor archive, available at https://gameboyfro.github.io/THE-HOUSE-OF-MARDENHOLT/
- **Chronicles:** Five published, dated chapters (4–8 November 2026). Chapter VI (9 November) is being drafted privately and is not published.
- **Features:** Wanderer's Chronicle, Journey Timeline, Azeroth Atlas (including dated field-note locations awaiting their chapters), and Companions Ledger with nine illustrated dossiers.
- **Editor:** Private offline HTML editor, not part of the public repository; its browser-local drafts are not automatically synced to GitHub.
- **Map:** Existing schematic Atlas retained pending a redesign approved by the site owner.

## Safety first
This repository is intended to hold only the **public Visitor website** and documentation.
**Never upload** the private Editor, browser-storage backups, unpublished chapters, credentials, tokens, or personal information here. If the repository is changed to Public, all committed files and their history become publicly visible.

## Publishing and preview workflow
1. Prepare chapter material and local editor backups privately; do **not** commit the private editor, account tokens, or unpublished drafts.
2. Open a draft pull request from a feature branch to `main`.
3. Verify story, artwork assets, chapter metadata, Atlas locations and companion appearances.
4. Merge only after owner approval. The live visitor site is served from `main`.

## Update rules
Every future release must update `CHANGELOG.md` with the date, version, **Added / Changed / Fixed / Removed / Pending**, and list of affected files. Preserve the last working release before overwriting `index.html`.
Do not modify approved images, journal entries or character details without explicit instructions.

## Future improvements
- **Notes from Fellow Wanderers**: moderated visitor comments, requiring a separate service.
- **Atlas accuracy:** replace approximate marker placements with verified geographic coordinates when suitable.
- **Publishing workflow:** safer synchronization from the private editor and automated validation.

## Important files
- `index.html` — live read-only Visitor website and illustrated Chronicle.
- `assets/` — public site artwork, Chronicles plates, nine approved companion portraits and Chronicle illustrations.
- `.nojekyll` — serve the static website directly through GitHub Pages.
- `README.md` — project and deployment guide.
- `CHANGELOG.md` — version-by-version record.

*The Oath Outlives the Crown.*
