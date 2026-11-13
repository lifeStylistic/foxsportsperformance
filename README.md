# Fox Sports Performance

Static marketing site for Fox Sports Performance personal training, styled to match the STYL (styl.inc) design system. Includes the live STYL booking calendar embed.

## Files
- `index.html` — homepage; the hero links to the schedule via a calendar screenshot
- `schedule.html` — full STYL calendar (all sessions)
- `group-training.html` — group workshops landing page; STYL calendar filtered to the `group-training` tag
- `private-training.html` — Private Training landing page; STYL calendar filtered to the `one-on-one` tag (old `/one-on-one` address redirects here)
- `assets/hero-montage.mp4` / `assets/hero-montage-mobile.mp4` — homepage background video (17 s, muted loop; the smaller file loads on phones)
- `assets/hero-poster.jpg` — still frame shown while the video loads, or instead of it when reduced motion is requested
- `assets/fox-logo-light.png` — white-and-grey logo for dark backgrounds, used in the header on every page (if missing, the text name is shown instead)
- `assets/fox-logo-wide.png` — wide full-colour logo for light backgrounds (not currently used on the site)
- `assets/fox-logo.png` — square logo, used as the browser-tab favicon
- `assets/fox-logo-web.png` — earlier trimmed copy of the square logo; no longer referenced by the site
- `styles.css` — design tokens (colors, fonts) taken from styl.inc
- `netlify.toml` — Netlify config (no build step; publishes the repo root)

## Deploy on Netlify
New site → Import from GitHub → pick this repo → leave the build command empty, publish directory `.`.

## Homepage video credits
The background montage is cut from free stock clips from [Mixkit](https://mixkit.co) (Mixkit Free License: free for commercial use, no attribution required):
43484 (dribbling), 28951 (cone dribbling drill), 42546 (agility ladder), 588 (sprint start), 32792 (sprint).
Swap in your own training footage any time by replacing the two `hero-montage` files.
