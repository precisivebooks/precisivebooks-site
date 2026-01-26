# Precisive Books LLC Website

This is the Jekyll static site for Precisive Books LLC, hosted on Netlify.

## Local Development

### Prerequisites

- Ruby 3.1 or higher
- Bundler gem

### Setup

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Build the site:
   ```bash
   bundle exec jekyll build
   ```

3. Serve locally:
   ```bash
   bundle exec jekyll serve
   ```

4. Open browser: http://localhost:4000

## Deployment

This site is configured to deploy automatically to Netlify when you push to the main branch.

### Manual Deployment Steps

1. Push to GitHub repository
2. Netlify will automatically detect and deploy
3. Connect custom domain in Netlify dashboard

## Site Structure

- `_config.yml` - Site configuration
- `_layouts/` - HTML layouts
- `_includes/` - Reusable components
- `assets/` - CSS, JS, and images
- Root markdown files - Pages (index.md, contact.md, etc.)

## Contact

For questions about this site, contact matthew@precisivebooks.com
