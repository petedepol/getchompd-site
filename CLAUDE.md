# Chompd Website — Project Context

## Overview
Marketing/landing site for Chompd, an AI-powered subscription tracker iOS app. Single-page static site.

## Structure
- `index.html` — main landing page (all sections: hero, features, screenshots, pricing, FAQ, etc.)
- `compare/chargeback-alternative.html` — comparison/SEO page
- `privacy/index.html` — privacy policy
- `robots.txt` / `sitemap.xml` — SEO files
- `screenshots/` — app screenshot PNGs
- `piranha_*.png` — mascot illustrations used throughout the site

## Key Notes
- Static HTML/CSS site — no build step, no framework
- All styles are inline in `index.html` `<style>` block
- Mobile responsive styles at `@media (max-width: 768px)` in `index.html`
- FAQPage structured data (JSON-LD) is embedded in `<head>`
- OpenGraph + Twitter Card meta tags reference `images/og-image.jpg` — **this file does not exist yet** (pending)
- Apple Smart App Banner meta tag is commented out at `index.html:17` — needs real App Store ID

## Pending Items
- Add `og-image.jpg` (1200x630) to `images/` directory
- Uncomment Apple Smart App Banner and add App Store ID
- Submit site to Google Search Console
