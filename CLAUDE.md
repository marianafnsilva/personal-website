# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal portfolio website for Mariana Silva built with vanilla HTML and CSS only. No build tools or frameworks.

## Architecture

**Structure:**
- Single-page static website
- Vanilla HTML/CSS (no JavaScript frameworks or build tools)
- Responsive design with mobile-first approach

**Design System:**
- Dark theme with modern minimalist aesthetic
- Primary fonts: Space Grotesk (headings), Inter (body)
- Color palette: Dark charcoal background (#1b1917), bright blue accent (#60a5fa), off-white text (#f3f0eb)
- Responsive breakpoints: 810px (mobile), 1024px (tablet), 1440px (desktop)

## Development

**Running Locally:**
```bash
# Simple HTTP server (Python 3)
python3 -m http.server 8000

# Or using PHP
php -S localhost:8000

# Or using Node.js (if http-server is installed)
npx http-server -p 8000
```

Then open `http://localhost:8000` in your browser.

**File Organization:**
- `index.html` - Main HTML file
- `styles.css` - All styles in a single CSS file (or organized into separate files if complexity grows)
- Assets organized in dedicated folders (images/, fonts/, etc.)

## Design Constraints

- HTML and CSS only - no JavaScript frameworks or build tools
- Maintain accessibility standards (semantic HTML, ARIA labels where needed)
- Responsive design across all viewport sizes
- Performance-optimized (font subsetting, efficient CSS)
