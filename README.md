# Fox Sports Performance

Static marketing site for Fox Sports Performance personal training, styled to match the STYL (styl.inc) design system. Includes the live STYL booking calendar embed.

## Files
- `index.html` — homepage; the hero links to the schedule via a calendar screenshot
- `schedule.html` — live STYL calendar embed
- `assets/calendar-preview.jpg` — calendar screenshot used on the homepage
- `assets/fox-logo-light.png` — white-and-grey logo for dark backgrounds, used in the header on every page (if missing, the text name is shown instead)
- `assets/fox-logo-wide.png` — wide full-colour logo for light backgrounds (not currently used on the site)
- `assets/fox-logo.png` — square logo, used as the browser-tab favicon
- `assets/fox-logo-web.png` — earlier trimmed copy of the square logo; no longer referenced by the site
- `styles.css` — design tokens (colors, fonts) taken from styl.inc
- `netlify.toml` — Netlify config (no build step; publishes the repo root)

## Deploy on Netlify
New site → Import from GitHub → pick this repo → leave the build command empty, publish directory `.`.
