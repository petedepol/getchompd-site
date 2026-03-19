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
- OpenGraph + Twitter Card meta tags reference `images/og-image.jpg`
- Apple Smart App Banner is active with App Store ID `6759305263`
- Site submitted to Google Search Console
