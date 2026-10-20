# Compress-E — Official Web Application

The official web compressor for **Compress-E** by Oshie Labs.

Fast, client-side, privacy-first image and photo compression directly in the browser. 

## Key Features

- **100% On-Device Processing:** Images are compressed entirely within the browser via HTML5 Canvas. Zero photos are ever uploaded to cloud servers.
- **Precision KB Targeting:** Specify exact target size constraints for job portals, exam uploads, and document attachments.
- **Multi-Format Support:** JPG, PNG, and WebP compression with real-time quality sliders.
- **Legal Compliance:** Integrated Privacy Policy (`/privacy.html`), Terms of Service (`/terms.html`), and Google `app-ads.txt`.

## Project Structure

```
├── public/                 # Static assets, legal pages, Cloudflare headers
│   ├── _headers            # Cloudflare Pages security & caching headers
│   ├── app-ads.txt         # Google AdMob verification
│   ├── privacy.html        # Official Privacy Policy
│   ├── terms.html          # Official Terms of Use
│   └── assets/             # Production application bundle
├── src/                    # React + TypeScript source components
├── index.html              # Main HTML entry
├── vite.config.ts          # Vite build configuration
└── package.json            # Dependencies & build scripts
```

## Local Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build production bundle
npm run build
```

## Deployment

Configured for zero-config deployment on **Cloudflare Pages**, **Vercel**, or **Netlify**.
Build output directory: `dist` (or `public` for static fallback).
