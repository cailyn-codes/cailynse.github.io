# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a personal portfolio website for Cailyn Edwards, a Security Engineer & CNCF Ambassador. The site is hosted on GitHub Pages and uses the custom domain `cailynse.ca`.

## Architecture

This is a static HTML/CSS website with no build system or package management. The site consists of:

- **Static HTML pages**: `index.html` (portfolio), `resume.html`, `videos.html`, `blog.html`, `photos.html`
- **Styling**: Single `style.css` file with terminal/cyberpunk theme
- **No JavaScript framework**: Uses vanilla JavaScript for navigation functionality
- **GitHub Pages hosting**: Deployed automatically when changes are pushed to the `master` branch

## File Structure

- `index.html` - Main portfolio page with hero section, experience, and skills
- `resume.html` - Resume/CV page  
- `videos.html` - Conference talks and video content
- `blog.html` - Blog posts and articles
- `photos.html` - Photo gallery
- `style.css` - Complete styling with terminal/cyberpunk theme and responsive design
- `CNAME` - Custom domain configuration for GitHub Pages

## Development Workflow

Since this is a static site with no build process:

1. **Local development**: Open HTML files directly in browser or use a simple HTTP server
2. **Testing changes**: No automated tests - verify manually in browser
3. **Deployment**: Push changes to `master` branch - GitHub Pages auto-deploys
4. **Domain**: Site is accessible at `cailynse.ca` via GitHub Pages

## Styling Guidelines

The site uses a consistent terminal/cyberpunk aesthetic with:

- **Color scheme**: Purple gradients, terminal green, cyan accents
- **Typography**: `Fira Code` and `Source Code Pro` monospace fonts
- **Visual effects**: Scan lines, glitch animations, terminal cursor
- **Components**: Terminal-style cards, navigation with command prompts
- **Responsive design**: Mobile-first approach with hamburger menu

## Content Management

- **Professional focus**: Security engineering, Kubernetes, CNCF community
- **Conference content**: Speaking engagements, KubeCon presentations
- **Technical expertise**: Container security, cloud native technologies, Auth0
- **Community involvement**: CNCF Ambassador, Kubernetes SIG-Security co-chair