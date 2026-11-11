# Fox Sports Performance

Static marketing site for Fox Sports Performance personal training, styled to match the STYL (styl.inc) design system. Includes the live STYL booking calendar embed.

## Files
- `index.html` — homepage; the hero links to the schedule via a calendar screenshot
- `schedule.html` — live STYL calendar embed
- `assets/calendar-preview.jpg` — calendar screenshot used on the homepage
- `assets/fox-logo.png` — header logo (if missing, the text name is shown instead)
- `styles.css` — design tokens (colors, fonts) taken from styl.inc
- `netlify.toml` — Netlify config (no build step; publishes the repo root)

## Deploy on Netlify
New site → Import from GitHub → pick this repo → leave the build command empty, publish directory `.`.
