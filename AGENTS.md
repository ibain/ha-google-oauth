# AGENTS.md

## What this is

Two static pages (home page + privacy policy) for the Google OAuth consent screen of Ian's personal Home Assistant OAuth client. Google requires both URLs to publish the app out of Testing, which otherwise expires the HA login every 7 days. Served by GitHub Pages.

## Pickup

| | |
|---|---|
| Live | `https://ibain.github.io/ha-google-oauth/`, `…/privacy.html` |
| Deploy | Push to `main`; Pages serves the repo root |
| Used by | Google Cloud project `1089219471815`, Google Auth Platform → Branding (authorized domain `ibain.github.io`) |
| HA side | `~/GitHub-Personal/home-assistant` (Google Calendar integration) |

## Hard rules

- Keep the pages accurate: if the app's scopes or data use change, update `privacy.html`.
- Renaming or deleting the repo breaks the Branding URLs.
