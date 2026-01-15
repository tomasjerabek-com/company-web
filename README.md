# tomasjerabek.com

Personal website built with Astro and Tailwind CSS, deployed on GitHub Pages.

## Features

- ✅ Modern, responsive design with Tailwind CSS
- ✅ Static site generation for fast GitHub Pages deployment
- ✅ SEO optimized with sitemap.xml, robots.txt, and meta tags
- ✅ Tag-based technology showcase
- ✅ Improved content and messaging

## Development

```bash
# Install dependencies
npm install

# Start development server (runs on http://localhost:4321)
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

The site is configured for static export and GitHub Pages deployment. After building, the `dist/` folder contains all static files ready for deployment.

1. Build the site: `npm run build`
2. The `dist/` folder contains all static files
3. Deploy the contents of `dist/` to GitHub Pages

The sitemap is available at `/sitemap.xml` and robots.txt at `/robots.txt`.

## Project Structure

```
/
├── public/          # Static assets (images, CV, CNAME, robots.txt, sitemap.xml)
├── src/
│   ├── layouts/     # Layout components (Layout.astro)
│   ├── pages/       # Page components (index.astro, 404.astro)
│   └── components/  # Reusable components (currently empty)
├── dist/            # Build output (generated - deploy this to GitHub Pages)
└── astro.config.mjs # Astro configuration
```

## Technologies

The site showcases the following technologies in tag-based pills:
- Languages: Python, Dart, HTML, CSS, SASS, SQL, NoSQL
- Frameworks: Django, Flask, FastAPI, Falcon, Flutter, Astro, Tailwind
- Tools & Platforms: Supabase, Firebase, Cloudflare, GitHub, Cursor
- Enterprise: FileNet, Kofax, CIM DATABASE
