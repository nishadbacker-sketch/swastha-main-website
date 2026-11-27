# Swastha Learning Clinic — Main Website

This repository is for the public marketing website at **https://swasthalearning.com/**, not the Next.js portal.

## Source files

The original site is backed up in the user's Hostinger `public_html` directory. The production website is a standalone `index.html` with inline images and CSS, plus `robots.txt` and `sitemap.xml`.

**Do not deploy this repository while `index.html` is absent.** Import the prepared root website files first. Do **not** add the legacy `portal/` subdirectory or any `.git/` folder from the Hostinger backup.

## Planned launch

- Preserve the existing brand design and English/Malayalam language selection.
- Re-label the main form button **Go to Free Assessment**.
- Have the main form collect guardian and student information once.
- Open `https://portal.swasthalearning.com/free-assessment` in a new tab and use origin-checked `postMessage` to transfer the already entered details without URL query strings or browser storage.
- Assessment responses are submitted by the portal after all 25 questions; the main website itself does not write appointment records on button click.
- Deploy portal PR #97 and confirm the destination URL works before changing the public site.

The main website remains hosted and managed in Hostinger until its GitHub integration is configured.
