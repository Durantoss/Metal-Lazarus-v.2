# METAL LAZARUS // Containment Console

An early, **mobile-first interactive prototype** for an invite-only global metal music discovery platform.

## Live prototype features
- Dense cyberpunk dashboard with neon-green containment visuals
- Demo release radar and release calendar, with searchable/filterable entries
- Demo band profiles from several metal subgenres and countries
- Favorite bands and releases, persisted locally in the browser
- Responsive navigation optimized for iPhone and desktop
- Clearly labeled access-control roadmap

> **Important:** Every band, record, and release date in the current interface is a fictional placeholder. The app does not yet connect to a music metadata provider. Do not use the sample dates as actual release information.

## Test locally
Open `index.html` in a modern browser. No dependencies, build step, or API key required.

## Publish with GitHub Pages
This repository contains a GitHub Actions workflow at `.github/workflows/deploy-pages.yml` for hosting the **public demo**.

1. On GitHub, open **Settings → Pages**.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Go to **Actions**, open **Deploy Metal Lazarus Demo**, then choose **Run workflow** if it has not run automatically.
4. Once successful, GitHub Pages normally serves the demo at `https://durantoss.github.io/Metal-Lazarus-v.2/`.

If GitHub Pages is unavailable for your account/repository visibility, deploy the static `index.html` through a supported static host instead.

**Privacy warning:** A GitHub Pages site is publicly accessible, even if you later make the repository private. This prototype does not have authentication and must not contain private information.

## Next production milestones
1. Select and verify reliable worldwide release metadata sources; include original source links, correction workflow, time zones and provenance.
2. Build real band and release data models with canonical IDs and duplicate detection.
3. Add server-side invite-only authentication, owner/admin-only invitation issuance, expiring invite codes, database authorization checks, and protected endpoints.
4. Integrate search, personal profiles and server-backed favorites.
5. Invite 5–10 beta testers only after security and data-quality checks.

## Current limitations
- No live music data, member accounts, or backend
- Favorites are stored on the current device only
- No real invitation controls (the Access section is explanatory)
- No production security assurance

Built as a first UI proof of concept. Metal Lazarus // Resurrect the underground.
