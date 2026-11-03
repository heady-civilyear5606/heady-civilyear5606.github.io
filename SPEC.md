# SPEC — Saeed Garfan Digital Business Card

## Goal
A one-page, mobile-first contact website for Saeed Garfan (Sales Engineer, INOVEX Group).
People open it by scanning a QR code on his printed business card, then contact him or save his contact in one tap.

## Users
- Customers, partners and contacts who scan the QR code, mostly on phones (iPhone and Android).
- Saeed (owner) updates content only through Claude Code. No admin panel.

## Content (version 1, English only)
- Logo: text wordmark "INOVEX" with "GROUP" under it (temporary). The official logo file will be added later as assets/logo.png or assets/logo.svg.
- Tagline: INSPIRED BY INNOVATION
- Name: SAEED GARFAN
- Title: Sales Engineer
- Company: INOVEX Group
- Phone: +966 57 957 4240  (tel:+966579574240)
- WhatsApp: same number  (https://wa.me/966579574240)
- Email: s.garfan@inovex-group.com
- Company website: https://www.inovex-group.com/
- LinkedIn: https://www.linkedin.com/in/saeed-garfan-38985a441
- Location: Riyadh, Saudi Arabia (text only, no map link)
- About INOVEX (short section; wording must be approved by the company before publishing):
  - Coating systems: design, manufacturing, installation and support.
  - Authorized WAGNER reseller for the GCC and Middle East.
  - Technology partners: LESTA Robotics and Coatmaster.
  - INOVEX Care: maintenance, spare parts and support.

## Features (version 1)
1. One page (index.html) showing all the content above.
2. Action buttons: Call, WhatsApp, Email, Website, LinkedIn. External links open in a new tab.
3. "Save Contact" button that downloads a vCard file (saeed-garfan.vcf, vCard 3.0) with name, title, company, phone, email, website, LinkedIn and city.
4. Black and gold design matching the printed business card.
5. Mobile-first layout that works from 320px wide phones up to desktop.
6. Link preview (Open Graph tags) when the link is shared on WhatsApp or LinkedIn, plus a favicon.
7. Published on GitHub Pages at https://sgarfan-inovex.github.io/
8. QR code files pointing to the live URL: qr/qr-code.png (at least 1000x1000 px) and qr/qr-code.svg, dark code on a light background, with a quiet zone (white margin).

## Out of scope (later)
Arabic version, personal photo, CV PDF, visit counter, custom domain, contact form, admin panel, any backend or database.

## Page layout (one screen, top to bottom)
Header (logo + tagline) -> Identity (name, title, company) -> Action buttons -> Save Contact button -> Contact details list -> About INOVEX -> Footer (© year Saeed Garfan).

## Data stored
None. No cookies, no tracking, no forms, no personal data collected from visitors.

## Technology
Plain HTML + CSS (tiny JavaScript only if truly needed). No frameworks, no build step.
Files: index.html, styles.css, saeed-garfan.vcf, assets/ (icons, favicon, preview image), qr/.

## Design notes
- Background near-black (#0B0B0B to #151515). Gold accent around #C9A24A with a soft gradient to #E6C77A. Text white/silver (#EDEDED, #BFBFBF).
- Thin gold divider lines and a diagonal gold accent, like the printed card.
- One geometric sans-serif font from Google Fonts (for example Montserrat). Uppercase letter-spaced labels.
- Simple gold line icons as inline SVG (no icon library).
- Large tap targets (at least 44px high) and good text contrast.
- Light and fast: no heavy images.
