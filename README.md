# Restless & Wild — static site

## Structure

- `index.html` — main site
- `impressum.html` — legal page
- `assets/hero-blueprint.webp` — hero image
- `assets/about-photo.webp` — About photo

## Local fonts (recommended before going live)

The current HTML still references Google Fonts so the visual design remains identical until the font files are added locally.

Fonts used:
- Big Shoulders Display: 400, 600, 700, 900
- IBM Plex Mono: 400, 500
- IBM Plex Sans: 400, 500, 600

Download the web font files from the official font projects, put the `.woff2` files into `assets/fonts/`, then replace the three Google Fonts `<link>` lines in `index.html` and `impressum.html` with local `@font-face` declarations.

IBM Plex is published by IBM under the SIL Open Font License; the IBM project documents self-hosting and web font packages. Big Shoulders is also distributed under OFL-1.1.

For a simple static site, WOFF2 is preferred. You do not need a build system.
