# FIFA 2026 Album Tips Website - Design Specification

## Project Overview

**Project Name:** Album FIFA 2026 Tips
**Type:** SEO Content Website + Landing Page (Hybrid)
**Primary Goal:** Rank on Google for FIFA 2026 album keywords, drive traffic to swap26.pages.dev
**Target Audience:** Panini FIFA 2026 album collectors (primarily USA, UK, Canada, Australia, Mexico)
**Language:** English (primary)

---

## Brand Story & Mood

The website embodies the passion and nostalgia of collecting football stickers - that childhood excitement of completing something special. The mood is:
- **Energetic** - The thrill of the chase
- **Premium** - Like a collector's item
- **Trustworthy** - Real advice from real collectors
- **Modern** - Cutting-edge tools for a timeless hobby

---

## Design Philosophy

### Color Palette (Earth Tones - No Blue/Purple)
- **Primary:** `#D4380D` (Burnt Orange - energy, passion)
- **Secondary:** `#722F17` (Warm Brown - premium, collectible feel)
- **Accent:** `#F5A623` (Golden Amber - achievements, completion)
- **Background Light:** `#FDF8F3` (Warm Cream)
- **Background Dark:** `#1A1410` (Rich Dark Brown)
- **Text Primary:** `#2D2420` (Deep Brown)
- **Text Light:** `#FFFFFF`
- **Success:** `#52C41A` (Leaf Green)

### Typography
- **Headlines:** "Bebas Neue" - Bold, impactful, sports feel
- **Body:** "Inter" - Clean, modern, readable
- **Accent:** "Playfair Display" - For quotes and emphasis
- **Font Scale:**
  - H1: 64px / H2: 48px / H3: 32px / H4: 24px
  - Body: 18px / Small: 14px

### Layout
- **Grid:** 12-column with generous whitespace
- **Max Width:** 1440px container
- **Section Padding:** 80px vertical (desktop), 48px (mobile)
- **Card Radius:** 16px for premium feel

---

## Pages Structure

### 1. Homepage (`/index.html`)
- **Hero Section:** Video-led with animated title "Complete Your FIFA 2026 Album"
- **Featured Tips Section:** 4 key tips with icons
- **Album Stats Section:** Interesting numbers about the album
- **Popular Articles:** 6 article cards linking to content pages
- **App Promo Section:** "Why SWAP26 is the best tool"
- **FAQ Section:** Common questions
- **CTA Banner:** Direct link to swap26.pages.dev

### 2. Ultimate Guide (`/guide/index.html`)
- Complete article about the album
- Internal links to other pages
- Schema markup for article

### 3. Tips Collection (`/tips/index.html`)
- Grid of tip articles
- Category filters
- Related content

### 4. App Section (`/app/index.html`)
- Dedicated SWAP26 promotion
- Feature showcase
- How it works section

### 5. Trading Tips (`/trading/index.html`)
- Exchange strategies
- Safety tips
- Community links

---

## Hero Section (Video-Led)

**Video Requirements:**
- Resolution: 1080p minimum (1920x1080)
- Mood: Cinematic, football stadium atmosphere
- Loop: Yes, muted autoplay
- Fallback: Solid `#D4380D` background

**Hero Elements:**
- H1: "FIFA 2026 ALBUM GUIDE"
- Subtitle: "Your Complete Collection Companion"
- CTA Button: "Start Your Journey" → swap26.pages.dev
- Floating badge: "1012+ Stickers to Collect"

---

## Motion & Interactions

### Scroll Animations
- Fade-up on scroll (opacity 0→1, translateY 30px→0)
- Staggered animations for cards (100ms delay)
- Parallax on hero background

### Hover States
- Cards: Scale 1.02, shadow lift
- Buttons: Background shift, scale 1.05
- Links: Underline animation

### Transitions
- Page transitions: Smooth 300ms ease
- Color transitions: 200ms

---

## SEO Structure

### Meta Tags (Per Page)
```
Home: "FIFA 2026 Album Guide: Tips to Complete Your Collection | SWAP26"
Tips: "15 Tips to Complete FIFA 2026 Album Fast | SWAP26"
App: "Best App to Manage Your Panini 2026 Album | SWAP26"
```

### Schema Markup
- Organization schema
- Article schema for guides
- FAQ schema
- BreadcrumbList

### Internal Linking
- Every page links to swap26.pages.dev
- Contextual mentions of SWAP26 in content
- Breadcrumb navigation

---

## Content Strategy

### Pillar 1: Complete Album Guide
- What is the Panini FIFA 2026 album
- How many stickers (1012+)
- Exchange system explained
- Important dates

### Pillar 2: Completion Strategies
- How to get difficult stickers
- Best places to buy
- Trading techniques
- Getting rare stickers

### Pillar 3: Album Management
- Tracking missing stickers
- Apps and tools
- SWAP26 as the recommended solution

### Pillar 4: Problem Solving
- Damaged stickers
- Authenticity tips
- Beginner FAQ

---

## CTAs (Conversion)

1. **Primary CTA:** "Try SWAP26 Free" → swap26.pages.dev
2. **Secondary CTA:** "Start Managing Your Album"
3. **In-article CTA:** Mention SWAP26 naturally as the solution

---

## Technical Stack

- **Stack:** Pure HTML5 + CSS + Vanilla JS (no framework needed for static)
- **CSS:** Custom CSS with CSS variables
- **JS:** Minimal vanilla JS for animations
- **Icons:** Inline SVG (no external dependencies)
- **Fonts:** Google Fonts (Bebas Neue, Inter, Playfair Display)

---

## Asset Requirements

1. **Hero Video:** 1080p cinematic football/stadium footage
2. **Feature Icons:** 6 custom SVG icons for tips
3. **Album Mockup:** Stylized album illustration
4. **App Screenshots:** Phone mockups showing SWAP26 interface
5. **Background Patterns:** Geometric patterns with brand colors

---

## Performance Requirements

- LCP < 2.5s
- CLS < 0.1
- Mobile-first responsive
- Lazy loading for images
- Minimal external requests

---

## File Structure
```
album-fifa-2026-tips/
├── index.html
├── guide/
│   └── index.html
├── tips/
│   └── index.html
├── app/
│   └── index.html
├── trading/
│   └── index.html
├── sitemap.xml
├── robots.txt
├── spec.md
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── imgs/
│   └── [generated images]
└── videos/
    └── [hero video]
```