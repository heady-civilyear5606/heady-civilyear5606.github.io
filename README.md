# Saeed Garfan — Digital Business Card

A one-page, mobile-first contact website for Saeed Garfan (Sales Engineer, INOVEX Group).
It opens from the QR code on the printed business card.

Live site: https://sgarfan-inovex.github.io/

## Files
- `index.html` — the page
- `styles.css` — the styles
- `saeed-garfan.vcf` — contact card for the Save Contact button
- `assets/` — favicon, home-screen icon and link preview image
- `assets/fonts/` — Montserrat font files (self-hosted) and their license `OFL.txt`
- `qr/` — QR code to the live site (`qr-code.svg` for print, `qr-code.png` 1025x1025 px)
- `_config.yml` — tells GitHub Pages not to publish the .md files on the live site
- `SPEC.md` — what the site must contain
- `PLAN.md` — milestones and progress
- `CLAUDE.md` — rules for Claude Code

## View locally
Double-click `index.html` to open it in a browser. No build step needed.

## How to update contact info
The same details appear in several places. Change ALL of them, then test and commit.

| Detail | Where to change it |
|---|---|
| Phone / WhatsApp | `index.html`: Call button, WhatsApp button, Phone row (link + shown text), WhatsApp row (link + shown text). `saeed-garfan.vcf`: `TEL` line. `SPEC.md`: Phone and WhatsApp lines |
| Email | `index.html`: Email button, Email row (link + shown text). `saeed-garfan.vcf`: `EMAIL` line. `SPEC.md`: Email line |
| Company website | `index.html`: Website button, Website row (link + shown text). `saeed-garfan.vcf`: `URL` line. `SPEC.md` |
| LinkedIn | `index.html`: LinkedIn button, LinkedIn row (link + shown text). `saeed-garfan.vcf`: `item1.URL` and `X-SOCIALPROFILE` lines. `SPEC.md` |
| Name / title / company | `index.html`: `<title>`, description and Open Graph tags in `<head>`, Identity section, About text, footer. `saeed-garfan.vcf`: `N`, `FN`, `TITLE`, `ORG`. `SPEC.md`. The link preview image `assets/og-image.png` also shows the name and title |
| Bio (About) | `index.html`: About section. `SPEC.md`: About line |

Quick check after any change: search the project for the old value (for example the old phone number) and make sure nothing is left.
Note: the QR code does not need to change unless the site address changes.
