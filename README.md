# Yours, From Here — Letter Club Microsite

A separate, dependency-free static microsite for Lizelle's monthly letter club, related to Next Chapter Studio (https://next-chapter-studio.com/) but completely independent of the main site.

## What's included

- `index.html` — Homepage: hero, inside-the-envelope, editions, founder story, how it works, membership preview, and FAQ
- `styles.css` — Navy/cream/coral/sage palette, Georgia + Arial typography, responsive layouts
- `script.js` — Mobile navigation, edition detail dialogs, and current footer year
- `assets/` — Hero, stationery, and edition artwork (WebP) plus the `mark.svg` favicon

## Design tokens

- Navy: #071a3d
- Cream: #fbf7f1
- Coral: #ed6556
- Sage: #8fa48d
- Fonts: Georgia (serif headings/accents) and Arial (sans body) — system fonts, no remote font service

## How to run locally

Open `index.html` in your browser, or serve the folder with any static server:

```sh
python3 -m http.server 8080 --directory yours-from-here-microsite
```

Then open http://localhost:8080. No build step or install required.

## How it relates to Next Chapter Studio

The header wordmark links to `https://next-chapter-studio.com/` as the parent brand, and the footer links back to the main site. Aside from those links, this microsite is self-contained: it has no dependency on the Next Chapter Studio codebase, no shared stylesheets, and no build integration.

## How to publish

These are static HTML files. Host the whole folder (keeping `assets/` alongside the HTML) for free on:

- GitHub Pages
- Netlify Drop
- Vercel
- Any static host

## Notes

- All imagery is AI-generated concept artwork (watercolor/gouache direction). It is not evidence of manufactured products or actual founder photographs.
- Text is HTML, not embedded in screenshots.
- The preview intentionally contains no fake checkout, email collection, payment credentials, invented prices, reviews, follower counts, social links, or tracking scripts.
- Review the founder story, edition contents, pricing, shipping, and terms before public launch (see the launch checklist in the original design README).
