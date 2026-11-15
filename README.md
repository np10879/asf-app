# ASF App Showcase Pages

Static HTML scaffolds and Markdown briefs for the six core ASF app showcase pages. These are draft presentation templates, not a working application. All six final thumbnails are **Not started**.

## Preview locally

From the repository root:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000/pages/>. No build step, package installation, external fonts, or JavaScript is required. GitHub's file viewer shows HTML source; it does not run these pages.

## Project structure

```text
assets/css/app-pages.css       Shared responsive styles and page theme tokens
pages/index.html              Showcase index and navigation
pages/dashboard.html          Dashboard scaffold
pages/dashboard.md            Dashboard content and thumbnail brief
pages/analytics.html          Analytics scaffold
pages/analytics.md            Analytics content and thumbnail brief
pages/billing.html            Billing scaffold
pages/billing.md              Billing content and thumbnail brief
pages/team-management.html    Team Management scaffold
pages/team-management.md      Team Management content and thumbnail brief
pages/integrations.html       Integrations scaffold
pages/integrations.md         Integrations content and thumbnail brief
pages/settings.html           Settings scaffold
pages/settings.md             Settings content and thumbnail brief
thumbnails/thumbnail.jpg       Existing shared placeholder, preserved unchanged
```

## Page and thumbnail plan

| Page | Theme | Target thumbnail | Final artwork |
| --- | --- | --- | --- |
| [Dashboard](pages/dashboard.html) | Navy / teal KPI overview | 1280×720 px | Not started |
| [Analytics](pages/analytics.html) | Indigo / cyan charts and trends | 1280×720 px | Not started |
| [Billing](pages/billing.html) | Emerald invoice and plan cards | 1280×720 px | Not started |
| [Team Management](pages/team-management.html) | Violet avatars and role cards | 1280×720 px | Not started |
| [Integrations](pages/integrations.html) | Blue connected app tiles | 1280×720 px | Not started |
| [Settings](pages/settings.html) | Slate modular controls and toggles | 1280×720 px | Not started |

## Shared visual rules

- Export final thumbnails at **1280×720 pixels**, **16:9**, sRGB.
- Use consistent system-sans typography, navy backgrounds, rounded panels, and page-specific accents.
- Keep essential labels and focal elements at least 64 px from the thumbnail edges; check legibility at 320×180.
- Use draft/demo data only. Do not include real financial information, credentials, or personal details.
- Every HTML page currently references `../thumbnails/thumbnail.jpg` with explicit dimensions and accessible placeholder text.
- Planned final files are `thumbnails/<page-slug>.jpg`; they do not exist yet. After approval, add each asset and update its page's image source and alt text. Do not overwrite the shared placeholder.

## Review checklist

- [ ] Approve page copy and visual themes.
- [ ] Produce and approve six page-specific thumbnails.
- [ ] Replace placeholder references with approved assets.
- [ ] Review keyboard navigation, mobile layout, image crops, and contrast.
- [ ] Review and merge the feature branch separately; no deployment is configured here.
