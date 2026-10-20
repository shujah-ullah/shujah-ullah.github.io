# shujah-ullah.github.io

Personal portfolio of **Shujah Ullah** — Control Systems Technician at an 1100MW power plant, OT cybersecurity practitioner, and founder of [Teckovia](https://teckovia.tech).

Live at: https://shujahullah.me (custom domain — see `CNAME`)

## Files
- `index.html` — the whole portfolio (single page, no build step)
- `styles.css` — dark theme, responsive
- `script.js` — mobile nav, scroll reveal, current year
- `assets/profile.png` — portrait
- `CNAME` — custom domain `shujahullah.me` (do not delete)

## Publish / update
Copy these files to the root of the `shujah-ullah/shujah-ullah.github.io` repo and push to `main`. GitHub Pages serves it automatically — no build settings needed.

## HTTPS note
If https://shujahullah.me shows a certificate error: in repo **Settings → Pages**, remove the custom domain, save, add `shujahullah.me` back, save, wait for the check to pass, then enable **Enforce HTTPS**. DNS is already correct (apex A records point to GitHub Pages: 185.199.108–111.153). For best practice, point the `www` CNAME to `shujah-ullah.github.io` at the registrar.
