# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Jekyll-based personal website and blog hosted on GitHub Pages at ishdhand.me. The site showcases research publications and contains a blog about quantum optics and quantum computing.

## Build Commands

```bash
# Install dependencies (to local vendor/bundle directory)
bundle config set --local path 'vendor/bundle'
bundle install

# Local development server (http://localhost:4000)
bundle exec jekyll serve

# Build static site to _site/
bundle exec jekyll build
```

## Deployment

GitHub Pages automatically builds and deploys when commits are pushed to the master branch. No CI/CD configuration is needed.

## Architecture

- **_config.yml** - Jekyll configuration (kramdown markdown, timezone, plugins)
- **_layouts/** - HTML templates (default.html for pages, post.html for blog posts)
- **_includes/** - Reusable snippets (analytics, disqus comments, mathjax for equations)
- **_pages/** - Static content pages (home, blog archive, publications)
- **_posts/** - Blog posts in YYYY-MM-DD-title.md format
- **css/** - Stylesheets (main.css, syntax.css for code highlighting)

## Key Integrations

- MathJax for rendering LaTeX equations in posts
- Disqus for blog comments
- Google Analytics/Tag Manager for tracking
- jekyll-feed and jekyll-sitemap plugins

## Blog Post Format

Posts use `<!--more-->` as excerpt separator. Front matter includes title, date, and optional math: true for MathJax.
