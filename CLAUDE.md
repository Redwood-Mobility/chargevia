# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

ChargeVia website - a Jekyll-based static site for "The EV Gas Station" brand. Fast charging infrastructure meets convenience store hospitality (Coz-E Corner partnership). Hosted on GitHub Pages at chargevia.net.

**Brand positioning**: Fun, playful, confident. Not premium/luxury (that's other brands). Not bare-bones parking lot plugs. Gas station heritage - converting old stations, applying proven format to EVs.

## Build & Development Commands

```bash
# Install dependencies
bundle install

# Local development server
bundle exec jekyll serve

# Build for production
bundle exec jekyll build
```

The site builds automatically on GitHub Pages when pushed to main branch.

## Project Structure

```
/
├── _config.yml              # Jekyll config, SEO settings
├── _layouts/default.html    # Base HTML template
├── _includes/               # Reusable components
├── assets/
│   ├── css/style.css        # All styles
│   ├── images/              # Logo variants (SVG, PNG)
│   └── js/main.js           # JavaScript
├── logos/                   # Old logo versions
└── index.html               # Homepage
```

Root-level reference materials (not part of build):
- `CHARGEVIA_WEBSITE_PROJECT_BRIEF.md` - Full brand positioning, voice/tone, and content guidelines

## Brand Guidelines

### Colors
- **Charge Orange**: `#FF6B35` - Primary brand color
- **Power Purple**: `#6A4C93` - Secondary brand color
- **Spark Yellow**: `#FFD700` - Accent (use sparingly)
- **Asphalt**: `#2C3E50` - Body text, grounding
- **Primary Gradient**: `linear-gradient(135deg, #FF6B35 0%, #6A4C93 100%)`

### Typography
- **Font**: Outfit (Google Fonts) - 400, 600, 700 weights
- Headlines: Outfit Bold (700)
- Body: Outfit Regular (400)

### Voice & Tone
- Fun & playful (think Buc-ee's, Wawa, Sheetz energy)
- Confident and direct, no corporate jargon
- Use "fast charging" not "ultra-rapid high-power DC infrastructure"
- Use "clean restrooms" not "premium amenities"

### Logo Files
Located in `assets/images/`:
- `chargevia-logo-primary.svg` - Full color
- `chargevia-logo-white.svg` - For dark backgrounds
- `chargevia-icon-*.svg` - Icon variants

### Social Handles
- @gochargevia (Twitter)

## Content Guidelines

- Pathfinder Rewards is the loyalty program (multi-network)
- Coz-E Corner is the convenience store partner
- Use "Coming Soon" and "Join Waitlist" for pre-launch content
- Focus: 10-12 DC fast chargers + convenience + clean restrooms
- See `CHARGEVIA_WEBSITE_PROJECT_BRIEF.md` for full messaging guidelines

## Dependencies

- Jekyll (via github-pages gem)
- jekyll-feed, jekyll-seo-tag, jekyll-sitemap plugins
- Google Fonts (Outfit)
