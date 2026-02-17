# Agents Documentation

## Project Description

Jekyll static website for Pencak Silat Bongkot Harimau martial arts school in Hamburg, Germany.

## Tech Stack

- Jekyll (Ruby-based static site generator)
- SCSS for styling
- Cayman theme
- WebP images

## Commands

### Development
```bash
bundle exec jekyll serve --baseurl ''
```

### Build
```bash
bundle exec jekyll build
```

## Commit Convention

Uses [conventional commits](https://www.conventionalcommits.org/) format:
- `feat:` - New features
- `fix:` - Bug fixes
- `chore:` - Maintenance tasks
- `perf:` - Performance improvements

Example: `fix: update external links to HTTPS`

## Site Structure

- `_config.yml` - Site configuration
- `_layouts/default.html` - Main layout
- `_pages/` - Content pages (training, pencak, contact, imprint)
- `assets/css/` - Stylesheets
- `assets/images/` - Image assets (WebP format)

## Language

German (with some English support)
