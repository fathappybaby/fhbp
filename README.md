# Fat Happy Baby Productions — Retro Build

Static two-page site, "Back to the 90s" aesthetic. Plain HTML / CSS / JS,
no build step. Works from `file://` by double-clicking `index.html`.

## Files

| File              | What it is                                          |
|-------------------|-----------------------------------------------------|
| `index.html`      | Cover page (this build).                            |
| `archive.html`    | Video archive — not built yet.                      |
| `css/style.css`   | Retro tokens + layout. Shared by both pages.        |
| `js/script.js`    | Live clock + fake visitor counter.                  |
| `.nojekyll`       | Tells GitHub Pages not to run Jekyll.               |

## Fonts

Pulled from Google Fonts via `<link>` in `index.html`:

- **Press Start 2P** — the wordmark.
- **IBM Plex Mono** — everything else.

## Local sanity check

```bash
# From this folder:
xdg-open index.html     # Linux
open index.html         # macOS
```

Or `python3 -m http.server 8000` and visit `http://localhost:8000/` if the
`file://` origin trips any browser-strict CSS/JS.

## Design notes

See `../working/plan1.md` for the full style research (fonts, palette,
layout moves), decisions made, and the deferred items for the archive page.
