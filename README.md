# Stay Nivas

A hospitality journal reviewing boutique and design-forward hotels through the lens of feeling, presence, and cultural depth.

**Domain:** staynivas.com (Cloudflare Pages)

## Development

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # Build to dist/
npm run preview  # Preview built site
```

## Documentation

- [Brand Style Guide](docs/STYLE-GUIDE.md)
- [Editorial Guide](docs/EDITORIAL-GUIDE.md)
- [GM Strategy](docs/GM-STRATEGY.md)

## Tech Stack

- [Astro](https://astro.build) static site generator
- Deployed to Cloudflare Pages
- Cormorant Garamond + Inter typography
- No JavaScript on the client (pure static HTML/CSS)

## Content Structure

```
src/
  pages/
    index.astro              # Homepage with founder's note + review cards
    reviews/
      [property-slug].astro  # Individual review pages
  layouts/
    Base.astro               # Shared layout
  components/
    ReviewCard.astro         # Review card for homepage
  styles/
    global.css               # Brand tokens + base styles
public/
  images/
    [property-slug]/         # Photos per property
docs/
  STYLE-GUIDE.md
  EDITORIAL-GUIDE.md
  GM-STRATEGY.md
```
