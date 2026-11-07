# THE HOUSE OF MARDENHOLT
**House Mardenholt — The Guardian Oak**  
*The Wanderer's Chronicle: the recorded adventures of Ser Atte Mardenholt in World of Warcraft: Forever.*

## Status
- **Repository documentation:** prepared (7 November 2026).
- **GitHub Pages website:** **not deployed**.
- **Visitor HTML:** uploaded as `index.html` (the three-chapter Visitor export, prepared for GitHub Pages).
- **Published journal chapters:** Chapter I (4 Nov), Chapter II (5 Nov) and Chapter III (6 Nov 2026), including 7 illustrations. All 14 House artwork files are also present.
- **Per-chapter visitor notes and adventure map:** planned, **not yet implemented**.

## Safety first
This repository is intended to hold only the **public Visitor website** and documentation.
**Never upload** the private Editor, browser-storage backups, unpublished chapters, credentials, tokens, or personal information here. If the repository is changed to Public, all committed files and their history become publicly visible.

## How to publish
1. The published Visitor export has been prepared and uploaded. **Keep the private Editor and its backups outside this repository.**
2. For GitHub Free, change repository visibility to **Public** under **Settings → General → Danger Zone → Change repository visibility**. **Only do this after reviewing the published content.** On eligible paid plans, Pages can also publish from a private repository, but the resulting Pages site is publicly accessible.
3. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main**, **/(root)**, and **Save**.
4. When GitHub says the site is published, verify the **Visit site** link in the Pages settings and check that the journal contains all three chapters and their images.

Expected project Pages URL *after successful deployment*:
`https://gameboyfro.github.io/THE-HOUSE-OF-MARDENHOLT/`
This URL is **not verified live**.

## Update rules
Every future release must update `CHANGELOG.md` with the date, version, **Added / Changed / Fixed / Removed / Pending**, and list of affected files. Preserve the last working release before overwriting `index.html`.
Do not modify approved images, journal entries or character details without explicit instructions.

## Future features (not live)
- **Notes from Fellow Wanderers**: moderated visitor messages beneath each chapter; requires an external comment storage/moderation service.
- **The Wanderer's Map**: interactive locations and routes compiled from chapter location metadata, updated on publishing.
- **Companions of the Road**: cross-reference characters and relevant chapters.

## Important files
- `index.html` — published Visitor website with three chapters (uploaded, **not deployed**).
- `assets/` — 14 House artwork files and 7 Chronicle illustrations, extracted losslessly from the approved Visitor export.
- `.nojekyll` — serve the static website directly through GitHub Pages.
- `README.md` — project and deployment guide.
- `CHANGELOG.md` — version-by-version record.

*The Oath Outlives the Crown.*
