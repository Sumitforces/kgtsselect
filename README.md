# KGTS Selections 2026-27

Landing page for the KGTS (Krishna Gyan Temple Society?) Fresher's and Sophomore selections for the 2026-27 academic year.

## Overview

A single-page, fully responsive static site that presents two sign-up links:

- **KGTS Fresher's Selections 2026-27** — Google Form
- **KGTS Sophomore Selections 2026-27 : Core Team** — Google Form

## Tech Stack

- Plain HTML5 + CSS3
- No frameworks, no build step, no dependencies

## Local Development

Open the page directly in a browser, or serve it with any static server:

```bash
python -m http.server 8000
# or
npx serve .
```

Then visit `http://localhost:8000`.

## Deployment

Hosted on [Vercel](https://vercel.com). Because this is a static site, no build command or output configuration is required.

### Deploy via CLI

```bash
npm i -g vercel
vercel          # preview deploy
vercel --prod   # production deploy
```

### Deploy via GitHub

1. Push this repository to GitHub.
2. On Vercel, click **Add New → Project**.
3. Import this repository.
4. Leave the build settings at their defaults and click **Deploy**.

## Project Structure

```
.
├── index.html   # Single-page landing site (styles are inline)
├── vercel.json  # Static site config for Vercel
└── README.md
```

## License

[MIT](./LICENSE)