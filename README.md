# shujah-ullah.github.io

Personal portfolio of **Shujah Ullah** — founder building startups with Agentic AI, starting with [Teckovia](https://teckovia.tech). Background: Control Systems Technician at an 1100MW power plant, OT cybersecurity practitioner.

Live at: https://shujahullah.me (custom domain — see `CNAME`)

## Files
- `index.html` — the whole portfolio (single page, no build step)
- `styles.css` — dark theme, responsive
- `script.js` — mobile nav, scroll reveal, current year
- `assets/profile.jpg` — portrait photo (also embedded in `index.html`, see note below)
- `CNAME` — custom domain `shujahullah.me` (do not delete)

## Publish / update
Copy these files to the root of the `shujah-ullah/shujah-ullah.github.io` repo and push to `main`. GitHub Pages serves it automatically — no build settings needed.

## HTTPS note
If https://shujahullah.me shows a certificate error: in repo **Settings → Pages**, remove the custom domain, save, add `shujahullah.me` back, save, wait for the check to pass, then enable **Enforce HTTPS**. DNS is already correct (apex A records point to GitHub Pages: 185.199.108–111.153). For best practice, point the `www` CNAME to `shujah-ullah.github.io` at the registrar.

## Photo note
The hero photo is embedded in `index.html` as a data URI because the site was published through GitHub's API connector, which only accepts text files — this keeps the live page complete without a separate image upload. The standalone photo is `assets/profile.jpg`. To switch to the file version later: upload `assets/profile.jpg` to the repo (web UI: Add file → Upload files) and change the hero `<img>` `src` from the `data:image/jpeg;base64,...` value to `assets/profile.jpg`.
