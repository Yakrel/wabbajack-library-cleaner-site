# Wabbajack Library Cleaner Website

The official landing page and documentation site for the [Wabbajack Library Cleaner](https://github.com/Yakrel/wabbajack-library-cleaner) - a high-performance Rust tool for managing and cleaning up Wabbajack download directories.

**Live Site:** [cleaner.byetgin.com](https://cleaner.byetgin.com)

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
```

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
