# Profile README maintenance

This repository is the profile repository for [@walou444](https://github.com/walou444).

## Before updating

- Keep the public identity as **Kloups / Kloups Studio**.
- Verify every external URL before adding it; do not infer project URLs.
- Keep image `alt` text meaningful and prefer relative paths for repository assets.
- Check the README in both GitHub light and dark themes.
- Treat third-party analytics and icon images as optional enhancements. The linked profile and project descriptions must remain useful if a service is unavailable.

The banner is a standalone SVG at [`assets/banner.svg`](assets/banner.svg), so it can be edited without introducing a JavaScript build step.

## Visual system

- Keep the midnight, electric-blue, violet and cyan palette consistent across the banner and project cards.
- Project cards live in `assets/project-*.svg`; keep each card at the shared `760 × 240` viewBox and preserve its meaningful `title`/`desc` metadata.
- Link each card through Markdown in `README.md`, with descriptive alt text and the verified destination URL.
- SVG animations must remain decorative, lightweight and readable when motion is reduced or unavailable. Do not add embedded JavaScript, external font dependencies or CSS files.

## Analytics

The README uses public, third-party image endpoints for optional GitHub statistics, activity and streak views. The overview card uses GitHub Stats Extended; these services do not receive repository secrets and may be unavailable. Never replace the linked profile with fabricated values. Keep `username=walou444` and preserve the fallback note when editing these URLs.

Do not add a language card unless it returns meaningful data for this account. An empty analytics card is less useful than a smaller, deliberate statistics section.

Before publishing visual changes, validate SVGs as XML, check that every `assets/` reference exists, and inspect the README in both GitHub light and dark themes. No workflow or generated contribution asset is required for the current animated banner.
