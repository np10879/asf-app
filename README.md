# ASF App Showcase Pages

**Thumbnail workflow: 100% complete (6/6 delivered). Pending thumbnail items: 0.**

Six static HTML showcase scaffolds and matching Markdown briefs are connected to the six uploaded, page-specific JPEGs on `feature/app-pages`. These pages are presentation scaffolds, not a live application. Product copy and functional app implementation are outside the completed thumbnail-delivery workflow.

- [Canva folder — ASF App Thumbnails](https://www.canva.com/folder/FAHa-nM4pC8)
- [Notion project tracker](https://app.notion.com/p/ASF-App-Pages-Project-Tracker-41957d1adb2081a1a4f1c85055172df4)
- [Page index](pages/index.html)
- [Asset manifest](thumbnails/manifest.json)

## Preview locally

From the repository root:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000/pages/>. No build step, external fonts, JavaScript, or package installation is required. GitHub's file viewer displays HTML source; it does not run these pages.

## Delivered thumbnails

Every uploaded JPEG was decoded and verified at **1280×720 px (16:9)**. Each page title passed automated OCR readability checks at **320×180**.

| Page | Theme | Uploaded JPEG | Status |
| --- | --- | --- | --- |
| [Dashboard](pages/dashboard.html) | Navy / teal | [ASF — Dashboard — Thumbnail.jpg](ASF%20%E2%80%94%20Dashboard%20%E2%80%94%20Thumbnail.jpg) | Delivered |
| [Analytics](pages/analytics.html) | Indigo / cyan | [ASF — Analytics — Thumbnail.jpg](ASF%20%E2%80%94%20Analytics%20%E2%80%94%20Thumbnail.jpg) | Delivered |
| [Billing](pages/billing.html) | Emerald | [ASF — Billing — Thumbnail.jpg](ASF%20%E2%80%94%20Billing%20%E2%80%94%20Thumbnail.jpg) | Delivered |
| [Team Management](pages/team-management.html) | Violet | [ASF — Team Management — Thumbnail.jpg](ASF%20%E2%80%94%20Team%20Management%20%E2%80%94%20Thumbnail.jpg) | Delivered |
| [Integrations](pages/integrations.html) | Blue | [ASF — Integrations — Thumbnail.jpg](ASF%20%E2%80%94%20Integrations%20%E2%80%94%20Thumbnail.jpg) | Delivered |
| [Settings](pages/settings.html) | Slate | [ASF — Settings — Thumbnail.jpg](ASF%20%E2%80%94%20Settings%20%E2%80%94%20Thumbnail.jpg) | Delivered |

## Reference and asset conventions

The user's uploaded filenames are preserved at the repository root. HTML and Markdown use URL-encoded relative paths so spaces and em dashes resolve correctly. The six detail pages and all six index previews reference their corresponding delivered JPEG, with explicit 1280×720 dimensions and responsive 16:9 styling.

- `pages/<page-slug>.html`: showcase page, delivered image, and descriptive alt text.
- `pages/<page-slug>.md`: content brief, Canva source, and delivered asset link.
- `pages/index.html`: six page-specific thumbnail previews and navigation.
- `assets/css/app-pages.css`: shared responsive layout and theme tokens, unchanged.
- `thumbnails/manifest.json`: actual repository paths, image dimensions, source URLs, and checksums.
- `thumbnails/thumbnail.jpg`: original placeholder, preserved unchanged and no longer referenced by the HTML pages.

## Completed thumbnail workflow

- [x] Scaffold six HTML pages and six Markdown briefs.
- [x] Generate, approve, and save six editable Canva designs in the dedicated folder.
- [x] Verify all six uploaded JPEGs and their native dimensions.
- [x] Verify all six titles remain readable at 320×180.
- [x] Integrate all six detail-page images and six index previews.
- [x] Update descriptive page alt text, asset links, briefs, and delivery status.
- [x] Validate local references against the existing repository files.

## Scope

This closes thumbnail design, verification, repository integration, and handoff documentation on `feature/app-pages`. It does not claim that draft app copy is approved or live product functionality is implemented. Merge, production hosting, and deployment are separate activities and were not performed. `main`, the six uploaded JPEGs, and the original placeholder are preserved.
