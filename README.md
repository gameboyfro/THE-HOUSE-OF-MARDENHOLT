# THE HOUSE OF MARDENHOLT
**House Mardenholt — The Guardian Oak**  
*The Wanderer's Chronicle: the recorded adventures of Ser Atte Mardenholt in World of Warcraft: Forever.*

## Status
- **Repository documentation:** prepared (7 November 2026).
- **GitHub Pages website:** **not deployed**.
- **Visitor HTML:** must still be uploaded as `index.html`.
- **Published journal chapters:** not in the available Visitor template. Export the approved Visitor edition from the working Editor before deploying.
- **Per-chapter visitor notes and adventure map:** planned, **not yet implemented**.

## Safety first
This repository is intended to hold only the **public Visitor website** and documentation.
**Never upload** the private Editor, browser-storage backups, unpublished chapters, credentials, tokens, or personal information here. If the repository is changed to Public, all committed files and their history become publicly visible.

## How to publish
1. In the working **private Editor**, back up the Chronicle and generate a **published Visitor HTML** containing only the chapters you want visitors to see. Verify it locally first.
2. Rename that exported Visitor HTML to **`index.html`** (keep the `.html` extension).
3. Upload **`index.html`** to this repository's top level using **Add file → Upload files → Commit changes**.
4. For GitHub Free, change repository visibility to **Public** under **Settings → General → Danger Zone → Change repository visibility**. Read GitHub's warning before confirming. GitHub Pages on paid plans can also publish from private repositories, but the resulting Pages site is still publicly accessible.
5. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose **main**, **/(root)**, and **Save**.
6. When GitHub says the site is published, verify the **Visit site** link in the Pages settings and check that the journal contains the correct chapters and images.

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
- `index.html` — published Visitor website; **not uploaded yet**.
- `README.md` — project and deployment guide.
- `CHANGELOG.md` — version-by-version record.

*The Oath Outlives the Crown.*
