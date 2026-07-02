# Services Website Template

A static Astro + Tailwind CSS website template for local service businesses. All business-specific content lives in a single JSON file — no database, shop, or login required.

## Quick Start

```bash
npm install
npm run dev
```

Open [http://localhost:4321](http://localhost:4321) in your browser.

## Customize Your Business

Edit `src/data/business.json` to update:

- Business name, tagline, and description
- Contact info (phone, email, address, hours)
- Services list
- About page content and values
- Testimonials
- SEO title and description
- Google Maps embed URL

## Pages

| Route       | Description                          |
|-------------|--------------------------------------|
| `/`         | Home — hero, services preview, testimonials |
| `/about`    | Company story and values             |
| `/services` | Full services list and process       |
| `/contact`  | Contact info, form, and map          |

## Components

- `Header.astro` — Sticky nav with mobile menu
- `Footer.astro` — Contact info, hours, and links
- `ServiceCard.astro` — Reusable service card
- `ContactCTA.astro` — Call-to-action banner
- `MapEmbed.astro` — Google Maps iframe placeholder

## Build for Production

```bash
npm run build
npm run preview
```

Static output is generated in the `dist/` folder, ready to deploy to Netlify, Vercel, Cloudflare Pages, or any static host.

## Contact Form

The contact form is a static placeholder. Connect it to a form service (Formspree, Netlify Forms, etc.) or your own backend to receive submissions.
