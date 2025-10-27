# Ameya's Radiology AI Blog

## Overview
This is a Jekyll-based static site blog discussing AI in radiology. The blog features an in-depth article titled "Should I have become a radiologist? The hype versus reality of radiology AI, AI in general and the road ahead."

## Project Structure
- **Jekyll Static Site Generator**: Using the `github-pages` gem which includes Jekyll 3.10.0
- **Theme**: jekyll-theme-minimal (GitHub Pages compatible theme)
- **Content**: Markdown-based content in `index.md`
- **Assets**: Images stored in `assets/img/` directory
- **Configuration**: `_config.yml` for site settings

## Recent Changes (October 27, 2025)
- Imported from GitHub repository
- Configured for Replit environment
- Updated Jekyll theme reference from `minimal` to `jekyll-theme-minimal`
- Set up workflow to serve on port 5000 with host 0.0.0.0
- Configured server with livereload for development

## Running the Project
The site runs automatically via the "Jekyll Server" workflow which executes:
```bash
bundle exec jekyll serve --host 0.0.0.0 --port 5000 --baseurl "" --livereload
```

## Technical Details
- **Ruby Version**: 3.3 (via Replit modules)
- **Jekyll Version**: 3.10.0 (from github-pages gem)
- **Server Port**: 5000
- **Host**: 0.0.0.0 (required for Replit proxy)
- **Live Reload**: Enabled for automatic updates during development

## Dependencies
Managed via Gemfile:
- `github-pages` gem (includes Jekyll and GitHub Pages compatible plugins)
- `webrick` (required for Jekyll 3.x on Ruby 3.x)

## Site Configuration
Production URL: https://ameyarad.github.io/RadiologyAI
Development: Uses empty baseurl for local development

## Content
The main article discusses:
1. What is radiology
2. AI model training in radiology
3. Radiology foundation models
4. Current reality of AI in radiology
5. Deep learning and reasoning limitations
6. Effects on radiology education
