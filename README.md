# Wabbajack Library Cleaner Website

Website for the Wabbajack Library Cleaner project.

## Tech Stack

- **Astro** - Static site generator
- **Tailwind CSS v4** - Styling
- **TypeScript** - Type safety
- **GitHub Actions** - CI/CD

## Local Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment

The site automatically deploys to GitHub Pages when pushing to `main` branch.

### Custom Domain Setup

1. In GitHub repo settings → Pages, add custom domain: `cleaner.byetgin.com`
2. Add DNS CNAME record:
   - Host: `cleaner`
   - Value: `yakrel.github.io`
3. Wait for DNS propagation
4. Enable "Enforce HTTPS"

## Project Structure

```
website/
 src/
   ├── components/     # Reusable Astro components
   ├── layouts/        # Page layouts
   ├── pages/          # Page routes
   └── styles/         # Global CSS
 public/
   └── screenshots/    # App screenshots
 .github/
   └── workflows/      # CI/CD
 astro.config.mjs    # Astro config
```
