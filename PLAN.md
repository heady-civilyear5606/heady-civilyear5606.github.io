# PLAN — Saeed Garfan Digital Business Card

## Milestone 1 — Structure and content
- [x] Check git is installed; set up git, .gitignore, README.md
- [x] index.html with all content from SPEC.md, clear sections, working links (tel, WhatsApp, mailto, website, LinkedIn)
- [x] Minimal styles.css (basic reset only, no design yet)
How to test: open index.html in a browser by double-clicking it. All content is visible and every link opens the right thing.

## Milestone 2 — Black and gold design
- [x] Full design from SPEC.md design notes, mobile-first
- [x] Gold line icons on the buttons and contact list
How to test: open in the browser, then use the browser's mobile view (F12 -> device toolbar) at 375px and 320px. Nothing overflows, buttons are easy to tap, it looks like the card.

## Milestone 3 — Save Contact (vCard)
- [x] saeed-garfan.vcf (vCard 3.0) with all contact fields
- [x] "Save Contact" button that downloads it
How to test: click the button on the computer, open the downloaded file, check every field is correct.

## Milestone 4 — Final polish
- [ ] Favicon and link preview image (Open Graph tags, absolute URLs to https://sgarfan-inovex.github.io/)
- [ ] Page title and description
- [ ] Accessibility check (contrast, alt text, button labels) and quick speed check
How to test: page tab shows the icon and title; review the checklist Claude Code reports.

## Milestone 5 — Publish on GitHub Pages
- [ ] Create GitHub repository "sgarfan-inovex.github.io" (public) and push
- [ ] Turn on GitHub Pages
How to test: open https://sgarfan-inovex.github.io/ on the phone; test Call, WhatsApp, Email, links, and Save Contact on iPhone and/or Android.

## Milestone 6 — QR code
- [ ] Generate qr/qr-code.png (min 1000x1000 px) and qr/qr-code.svg for https://sgarfan-inovex.github.io/
- [ ] Dark on light, quiet zone, error correction level M or higher
How to test: scan the QR from the computer screen with 2 different phones; it opens the live site. Print a test copy at card size and scan it.
