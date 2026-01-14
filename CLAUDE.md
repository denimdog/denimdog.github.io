# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the marketing website for **Denim Dog LLC**, an independent iOS app development company. The site showcases the company's apps, starting with Music Stacks (an Apple Music client). Hosted on GitHub Pages at **denim.dog**.

## Tech Stack

Pure static HTML5 + CSS3 with no build system, package manager, or JavaScript framework. Jekyll is configured only for GitHub Pages hosting (theme specified but not actively used).

## Development Workflow

1. Edit HTML/CSS files directly
2. Commit to `main` branch
3. GitHub Pages auto-deploys

No local build or server required - open HTML files directly in a browser for preview.

## Content Structure

- **Root level**: Company landing page (`index.html`)
- **`/musicstacks/`**: App-specific pages including showcase, privacy policy, and terms of use
- **`musicstacks/styles.css`**: Shared styles for all Music Stacks pages

## Key Patterns

- **Dark mode**: Uses `@media (prefers-color-scheme: dark)` with CSS custom properties
- **Responsive design**: Mobile-first with `clamp()` for fluid typography/sizing
- **Accessibility**: Semantic HTML, focus states, reduced motion support
- **SEO**: Schema.org JSON-LD structured data, Open Graph meta tags, XML sitemap
