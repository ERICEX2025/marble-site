# Marble website

The public website for [getmarble.app](https://getmarble.app). This repository contains the static homepage, interactive product examples, privacy policy, and support page.

The iOS application and Supabase backend live separately in [ERICEX2025/marble](https://github.com/ERICEX2025/marble), typically checked out at `../Marble`.

## Local preview

Run `python3 -m http.server 4187 --bind 127.0.0.1` in this directory, then open http://127.0.0.1:4187. No build or dependencies are required.

## Publishing

The current public site is served by GitHub Pages, with `CNAME` pointing to `getmarble.app`. Preserve the existing Pages settings and DNS when changing content. Local edits are not published until the deployment branch is pushed.

Keep pricing, free-tier limits, model names, and product claims aligned with the iOS app and backend. Product examples are illustrative, not screenshots or individual predictions. The App Store URL was a placeholder; the refreshed page uses working demo and support links until a verified listing URL is available.
