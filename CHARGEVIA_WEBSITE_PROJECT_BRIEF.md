# ChargeVia Website Project Brief
**For Claude Code / Jekyll Implementation on GitHub Pages**

---

## Project Overview

Build a Jekyll-based website for **ChargeVia** (chargevia.com) to be hosted on GitHub Pages. ChargeVia is "The EV Gas Station" - fast charging infrastructure meets convenience store hospitality (Coz-E Corner partnership). Fun, quirky, confident brand that makes EV charging feel like stopping at your favorite gas station.

**Brand Positioning:**
- **What we are**: The modern EV gas station (10-12 fast chargers + Coz-E Corner convenience)
- **Not luxury**: Not premium destination charging (that's other brands)
- **Not bare-bones**: Not just parking lot plugs (we're a place with personality)
- **Gas station heritage**: Converting old stations where possible, applying proven format to EVs

---

## Brand Identity

### Core Positioning
- **Category**: The EV Gas Station
- **Tagline**: "Fast charging. Real convenience."
- **Promise**: The EV pit stop that doesn't suck
- **Voice**: Fun, playful, confident, no-nonsense
- **Audience**: Daily drivers, fleet operators, road-trippers who just want charging to work

### Visual Identity

**Colors:**
- **Charge Orange**: `#FF6B35` (RGB: 255, 107, 53) - Primary brand color
- **Power Purple**: `#6A4C93` (RGB: 106, 76, 147) - Secondary brand color
- **Spark Yellow**: `#FFD700` (RGB: 255, 215, 0) - Accent (use sparingly)
- **Asphalt**: `#2C3E50` (RGB: 44, 62, 80) - Body text, grounding
- **White**: `#FFFFFF` - Backgrounds, contrast

**Gradients:**
- Primary: `linear-gradient(135deg, #FF6B35 0%, #6A4C93 100%)`

**Logo:** Plug-pin icon (charging plug + location pin marker)
- Bold geometric shapes, gas station signage inspired
- Orange plug with purple outline, yellow lightning accent
- Available: primary (full color), white (dark backgrounds), orange (single-color), horizontal lockup

**Typography:** Outfit (Google Fonts)
- Headlines: Outfit Bold (700)
- Body: Outfit Regular (400)
- Buttons/CTAs: Outfit Bold (700)
- Fallback: `'Outfit', -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif`
- Import: `@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;700&display=swap');`

### Voice & Tone

**Personality:**
- Fun & playful (gas stations can be fun - see Buc-ee's, Wawa, Sheetz)
- Confident (we know what we're doing, we're cool about it)
- Direct (no corporate jargon, straight talk)
- Approachable (professional but not stuffy)

**Copy Examples:**
- "Fast charging + snacks + clean restrooms. The EV pit stop that doesn't suck."
- "10 fast chargers. Clean restrooms. Actual snacks (not vending machines)."
- "Stop here because it works. Not because you have to."

**What We Say vs. Don't Say:**
- ✅ "Fast charging" / ❌ "Ultra-rapid high-power DC infrastructure"
- ✅ "Clean restrooms" / ❌ "Premium amenities"
- ✅ "In and out" / ❌ "Seamless customer journey"

---

## Site Structure

### Primary Pages

#### 1. Homepage (`index.html`)
**Purpose:** Introduce ChargeVia concept, drive to key actions

**Sections:**
- **Hero**: 
  - Headline: "Fast charging. Real convenience."
  - Subhead: "The EV gas station you actually want to stop at. 10+ fast chargers + Coz-E Corner snacks + clean restrooms. In and out before your coffee gets cold."
  - CTA: "Find a Station" + "Join Pathfinder" (secondary)
  - Background: Gradient (orange→purple) or hero image of ChargeVia station

- **The Format** (3-column):
  - **Fast Charging**: "10-12 DC fast chargers. No waiting. No drama."
  - **Real Convenience**: "Coz-E Corner convenience store. Snacks, drinks, clean restrooms."
  - **In & Out**: "Quick pit stop. Not a destination. Just what you need."

- **Why ChargeVia** (benefits):
  - "Charge where you are" (city/suburban locations, not detours)
  - "Works every time" (99% uptime, real-time availability)
  - "Pathfinder Rewards" (flat-rate pricing, credits back, multi-network)
  - "Coz-E Corner convenience" (food, drinks, restrooms)

- **Gas Station Heritage**:
  - "New Life for Old Stations" section
  - "We're converting old gas stations into EV charging hubs. Same community spots, new energy."
  - Before/after imagery (if available)
  - Sustainability + nostalgia angle

- **CTA Section**: "Ready to charge?" with station finder + Pathfinder signup

#### 2. Locations (`locations.html`)
**Purpose:** Show where ChargeVia stations are/will be

**Key Content:**
- Interactive map or list of stations (coming soon)
- "We're building ChargeVia stations in cities and suburbs where drivers actually are."
- Email signup: "Get notified when we launch in your area"
- Station format description (10-12 chargers, Coz-E Corner, amenities)
- Future: Real-time availability, turn-by-turn directions

#### 3. The Format (`format.html` or part of About)
**Purpose:** Explain the ChargeVia station experience

**Key Content:**
- **What You Get**:
  - 10-12 DC fast chargers (150-350kW)
  - Coz-E Corner convenience store
  - Clean restrooms (we actually maintain them)
  - Covered charging bays
  - Real-time availability

- **How It Works**:
  1. Pull in (like a gas station)
  2. Plug in your EV
  3. Head to Coz-E Corner while charging
  4. Grab what you need, use the restroom
  5. Back on the road

- **ChargeVia + Coz-E Corner**:
  - Partnership explanation
  - "ChargeVia provides the charging. Coz-E Corner provides the hospitality."
  - Co-branded experience

#### 4. Pathfinder Rewards (`membership.html`)
**Purpose:** Explain Pathfinder Rewards network membership

**Key Content:**
- "Part of the Pathfinder Rewards network"
- Free to join, earn credits with every charge
- Flat-rate pricing (no time-of-use complexity)
- Works at ChargeVia and partner networks
- Tier structure:
  - Explorer (free): Base flat rate
  - Voyager: 5% credits back
  - Pioneer: 10% credits back + $100 annual credit
  - Trailblazer: 15% credits back + $500 annual credit (invite-only)
- CTA: "Join Free" (email capture)

#### 5. Fleet (`fleet.html`)
**Purpose:** B2B offering for fleet operators

**Key Content:**
- Fleet-specific benefits:
  - Predictable charging for delivery routes
  - Real-time availability (no guessing)
  - Fleet pricing (volume discounts)
  - 99% uptime (downtime costs money)
- Use cases: Delivery vans, rideshare, service vehicles
- "Charge where your routes are, not where infrastructure happens to be"
- CTA: "Contact Fleet Team"

#### 6. Partners (`partners.html`)
**Purpose:** Recruit site hosts and partners

**Key Content:**
- **For Property Owners**:
  - "Got an old gas station? We've got a business model."
  - "ChargeVia handles infrastructure. You host the location. We share revenue."
  - Ideal sites: Former gas stations, high-traffic retail, commercial properties
  - 0.5+ acres, good highway visibility

- **For Convenience Partners**:
  - Coz-E Corner partnership model
  - Retail + charging = complete experience
  - Revenue share opportunity

- CTA: "Partner With Us" (contact form)

#### 7. About (`about.html`)
**Purpose:** Company story and mission

**Key Content:**
- **Who We Are**: "We're building the EV gas station you actually want to stop at."
- **Our Mission**: "Make EV charging as convenient as filling up at your favorite gas station."
- **The Team**: Brief intro (founders, advisors)
- **Gas Station Heritage**: Converting old stations, community continuity
- **Pathfinder Network**: Multi-brand loyalty program participation
- **Contact**: Email, social handles

#### 8. FAQ (`faq.html`)
**Purpose:** Answer common questions

**Key Topics:**
- What is ChargeVia?
- How is ChargeVia different from other charging networks?
- What is Coz-E Corner?
- What is Pathfinder Rewards?
- What vehicles can charge here?
- How do I pay?
- Where are you building stations?
- Do you buy/convert old gas stations?

---

## Design Specifications

### Layout Principles
- **Bold & Energetic**: Orange/purple color scheme, confident typography
- **Clear Hierarchy**: Large headings, obvious CTAs, easy scanning
- **Mobile-First**: Most users on phones, optimize for small screens first
- **Gas Station Vibes**: Nods to retro signage without being kitsch

### Component Patterns

#### Buttons
- **Primary**: Orange background (#FF6B35), white text, bold
- **Secondary**: White background, orange border and text
- **Accent**: Purple background (#6A4C93), white text (use sparingly)
- **Size**: 16-18px text, generous padding (16px vertical, 32px horizontal)
- **Border Radius**: 8px
- **Hover**: Slightly darker shade or scale up slightly

#### Hero Section
- **Background**: Orange→purple gradient OR photo with overlay
- **Text**: White, large, bold
- **CTA**: White button with orange text OR orange button (high contrast)

#### Cards
- **Border**: 2px solid light gray or orange on hover
- **Padding**: 32px
- **Border Radius**: 12px
- **Shadow**: Subtle on hover

#### Typography Scale
- H1: 48-64px, Bold (700)
- H2: 36-40px, Bold (700)
- H3: 24-28px, Semi-Bold (600)
- Body: 16-18px, Regular (400)
- Small/Labels: 14px, Semi-Bold (600)

### Navigation
- **Desktop**: Horizontal nav, sticky on scroll
- **Mobile**: Hamburger menu
- **Items**: Home | Locations | The Format | Membership | Fleet | Partners | About
- **CTA in Nav**: "Find a Station" button (orange)

### Footer
- **Layout**: 4 columns (desktop), stacked (mobile)
  1. About ChargeVia + logo
  2. Quick Links (Locations, Membership, FAQ)
  3. Company (About, Fleet, Partners, Contact)
  4. Legal (Privacy, Terms, Accessibility)
- **Bottom Bar**: Copyright, "Part of Pathfinder Network" badge, social icons
- **Social Handles**: @chargevia (all platforms)

---

## Content Guidelines

### Messaging Dos
✅ "Fast charging where you actually are"  
✅ "The EV gas station"  
✅ "In and out before your coffee gets cold"  
✅ "ChargeVia with Coz-E Corner convenience"  
✅ "10 fast chargers. Clean restrooms. Real snacks."  
✅ "Part of the Pathfinder Rewards network"  

### Messaging Don'ts
❌ Technical jargon (kW, NOC, infrastructure-speak)  
❌ Overly corporate language ("stakeholders," "ecosystem")  
❌ Premium/luxury positioning  
❌ Overpromising (specific dates, locations before confirmed)  
❌ "Revolutionary" or "disrupting" language  

### Brand Personality in Copy
- **Headlines**: Bold, direct, a little cheeky
- **Body**: Conversational, helpful, no BS
- **CTAs**: Action-oriented, clear benefit
- **Error messages**: Friendly, apologetic, helpful

---

## Technical Specifications

### Jekyll Configuration
```yaml
title: ChargeVia
description: Fast charging. Real convenience. The EV gas station.
url: https://chargevia.com
baseurl: ""

# Build settings
theme: null
plugins:
  - jekyll-feed
  - jekyll-seo-tag
  - jekyll-sitemap

# Collections (if needed for locations)
collections:
  locations:
    output: true
    permalink: /locations/:name/

# Defaults
defaults:
  - scope:
      path: ""
    values:
      layout: default
      author: ChargeVia
```

### CSS Color Variables
```css
:root {
  --charge-orange: #FF6B35;
  --power-purple: #6A4C93;
  --spark-yellow: #FFD700;
  --asphalt: #2C3E50;
  --white: #FFFFFF;
  --light-gray: #F5F5F5;
}
```

### Logo Files
- `chargevia-logo-primary.svg` - Full color (orange/purple)
- `chargevia-logo-white.svg` - White for dark backgrounds
- `chargevia-logo-orange.svg` - Single-color orange
- `chargevia-logo-horizontal.svg` - Icon + wordmark lockup

PNG versions also available in multiple sizes (32px to 1920px).

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Performance
- Optimize images (WebP with fallbacks)
- Minimize CSS/JS
- Lazy load images below fold
- Target < 2s load time on 4G

---

## SEO & Metadata

### Primary Keywords
- EV charging station
- EV gas station
- Electric vehicle charging
- Fast EV charging
- DC fast charging
- Convenience charging
- ChargeVia

### Meta Descriptions
- **Homepage**: "ChargeVia is the EV gas station. Fast charging + Coz-E Corner convenience + clean restrooms. Part of Pathfinder Rewards. Coming to cities near you."
- **Locations**: "Find ChargeVia EV charging stations. 10+ fast chargers, Coz-E Corner convenience, clean restrooms. The modern gas station for EVs."
- **Membership**: "Join Pathfinder Rewards for flat-rate EV charging with credits back. Free membership works at ChargeVia and partner networks."

### Open Graph / Social
- **og:title**: "ChargeVia - The EV Gas Station"
- **og:description**: "Fast charging. Real convenience. The pit stop you actually want to make."
- **og:image**: Hero image or logo (1200×630px)
- **Twitter card**: summary_large_image

---

## Brand Assets

### Logo Usage
- Header: Horizontal lockup (180-240px width)
- Favicon: Primary logo (32px, 64px)
- Social: Primary logo (512px, 1024px)
- App icon: Primary logo with gradient background

### Imagery Style
- Gas station aesthetics (retro-modern, not vintage kitsch)
- Orange/purple color scheme visible
- Real people charging, using convenience store
- Clean, bright, welcoming (not dark or moody)
- Urban/suburban settings (not scenic nature)

### Placeholder Content
- Use "Coming Soon to [City Name]" for locations
- "Join waitlist" for pre-launch signups
- Show station format even without specific addresses
- Example pricing marked as examples only

---

## Development Phases

### Phase 1: Core Pages (MVP)
- Jekyll structure, layouts, includes
- Homepage with hero, benefits, CTA
- About page
- Basic styling (colors, typography, buttons)
- Mobile responsive
- Deploy to GitHub Pages

### Phase 2: Content Pages
- Locations (coming soon state)
- Membership (Pathfinder Rewards)
- Fleet page
- Partners page
- FAQ
- Legal pages (Privacy, Terms)

### Phase 3: Polish & Optimize
- Image optimization
- Performance tuning
- Accessibility audit (WCAG AA)
- Browser testing
- Content review and refinement

---

## Success Criteria

### User Experience
- ✅ Clear value prop within 5 seconds
- ✅ Easy to understand "EV gas station" concept
- ✅ Simple path to join Pathfinder or find stations
- ✅ Fun, welcoming personality comes through
- ✅ Mobile-friendly (most EV drivers use phones)

### Technical
- ✅ Loads in < 2s on 4G
- ✅ Lighthouse scores 90+ (Performance, Accessibility, Best Practices, SEO)
- ✅ WCAG AA accessible
- ✅ Works in all modern browsers
- ✅ GitHub Pages deployment successful

### Brand
- ✅ Orange/purple color scheme distinctive and consistent
- ✅ Fun/playful voice comes through without being unprofessional
- ✅ Gas station positioning is clear
- ✅ Coz-E Corner partnership explained well
- ✅ Pathfinder Network integration clear but secondary

---

## Contact for Questions

**Zak Winnick**  
Founder & CEO, ChargeVia  
zak@chargevia.com  
@chargevia (social media)

---

## Final Notes

**This is a pre-launch site.** The goal is to:
1. Establish ChargeVia brand and positioning
2. Explain the "EV gas station" concept
3. Build waitlist/interest before stations open
4. Test messaging and positioning

**Be transparent:** Use "Coming Soon" and "Join Waitlist" rather than pretending stations exist.

**Have fun with it:** The brand is playful and confident. Let that show in copy, design, and interactions. This isn't another boring CPO website.

---

**Project Brief Version:** 1.0  
**Brand Version:** ChargeVia v2.0 (Orange/Purple, Gas Station Positioning)  
**Last Updated:** December 2025
