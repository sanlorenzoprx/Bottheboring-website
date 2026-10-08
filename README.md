# Bot the Boring — Website

Cloudflare Pages website and installable PWA for **Bot the Boring** and the **Bot the Boring Stuff** educational newsletter.

## Project scope

- Vite + React frontend
- Responsive public website and standard informational pages
- Six-book series and 30-problem DIY resource library
- Free niche-specific worked examples (not individualized consulting)
- Newsletter signup (must be connected to a secure backend before activation)
- Optional automation information (no paid activation until the service is ready)

## Deployment boundary

Production deployment, DNS updates, paid activation, and newsletter sending require separate verification and authorization. Never commit API keys or subscriber data.

## Local development

Once the website source is imported:

```bash
npm install
npm run dev
npm run build
```

Cloudflare Pages build command: `npm run build`; output directory: `dist`. Configure SPA fallback and verify PWA behavior before production.

**Status:** Repository scaffold. The existing local website source has not yet been imported into this repository.
