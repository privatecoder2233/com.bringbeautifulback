# AGENTS.md

## Project

`com.bringbeautifulback` — "Bring Beautiful Back" coming-soon landing page.

A single static page. No build system, no package manager, no dependencies.

## Structure

- `index.html` — page markup and the (front-end only) notify-form handler
- `style.css` — all styling (dark editorial palette, grain, animated blobs, entrance reveals)
- No frameworks, libraries, or external JS. Only Google Fonts via `<link>`.

## Working here

- Pure HTML/CSS: keep it dependency-free and dependency-free-of-the-file.
- Fonts: display = "Cormorant Garamond" (serif), body = "Inter".
- Palette (in `style.css` `:root`): `--ink`, `--parchment`, `--champagne`, `--rose`, `--sage`.
- The email form is intentionally front-end only (demo). No backend exists.
- Keep responsive: the page must work from mobile up (see `@media` block in CSS).
- Verify changes by opening `index.html` in a browser.