# Ali Hassan | Online Quran & Islamic Studies Teacher

A responsive personal portfolio for introducing Ali Hassan's Quran, Tajweed, Qira'at, Islamic Studies, and foundational Arabic teaching. The site uses plain HTML, CSS, and JavaScript with a small Node.js static server; no third-party packages are required.

## Run locally

Install Node.js, open this folder in a terminal, and run:

```bash
npm start
```

Open the localhost URL printed in the terminal. The default port is 3000; if that port is already occupied, the server selects the next available port.

## Production build and Vercel deployment

Build the static production site with:

```bash
npm run build
```

This creates a `dist/` directory containing the deployable site. The included `vercel.json` configures Vercel to run this build and publish `dist/`. Import the project into Vercel or run `vercel --prod` from this folder; no additional runtime dependencies are needed.

## Contact links

The website includes the supplied email address and Pakistan mobile number. WhatsApp uses the international number format derived from the supplied local number: `+92 329 4801605`.

## Content and assets

Teaching history and qualifications follow the supplied portfolio documentation. Exact institutions, dates, language proficiency, portrait, and CV were not supplied, so the page does not invent them. The hero uses a remotely hosted Quran photograph from Unsplash; an approved personal portrait can replace it when available.
