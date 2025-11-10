# Stonk Wars Website - Version Comparison

This repository contains 7 different design variations for the Stonk Wars website. Each version explores different layouts, visual styles, and interaction patterns while maintaining the core content about the 24/7 AI Stock Market Show.

## Version Overview

| Version | Style | Hero Section | Layout | Market Tickers | Gallery | Animations |
|---------|-------|--------------|--------|----------------|---------|------------|
| **1** | Classic Landing Page | Video background + overlay text | Single column | None | 3x2 grid + lightbox | Minimal |
| **2** | Clean & Modern | Side-by-side (text + image) | Two column hero | TradingView + Polymarket (top & bottom) | Auto-carousel | Auto-rotating carousel |
| **3** | Clean & Modern | Side-by-side (logo inline with text) | Two column hero | TradingView + Polymarket (top & bottom) | Auto-carousel | Auto-rotating carousel |
| **4** | Bento Grid | Image grid background with overlay | Bento grid showcase | TradingView + Polymarket (top & bottom) | Bento grid cards | Hover scale effects |
| **5** | Sidebar Layout | Background carousel | Sticky sidebar navigation | Sidebar market prices | 3x2 grid | Carousel + fade-ins |
| **6** | Floating Glassmorphism | Centered with floating logo | Glassmorphic cards | Floating TradingView | 3x2 floating grid | Floating + glow effects |
| **7** | Minimalist | Full-screen video | Minimal typography | Compact TradingView | Asymmetric layout | Fade-in on scroll |

---

## Detailed Feature Comparison

### **Version 1: Classic Landing Page**
**File:** `1.html`

**Style:** Traditional landing page with dark theme (steel: #18191c, lava: #ff4e1b)

**Key Features:**
- **Hero:** Full-width video background (stonks1.mp4) with centered overlay text
- **Navigation:** Sticky header with GitHub link, mobile hamburger menu
- **Gallery:** Static 3x2 image grid with "Open as lightbox" button for video viewing
- **Features:** 3 horizontal cards with images and descriptions
- **Layout:** Single-column, traditional scroll-down structure
- **Market Data:** None
- **Unique Elements:** Video lightbox modal, commented-out CTA buttons, comprehensive About section

**Best For:** Users who want a straightforward, video-focused presentation with traditional navigation

---

### **Version 2: Clean & Modern**
**File:** `2.html`

**Style:** Modern dark theme with cleaner aesthetics (steel: #0f1115)

**Key Features:**
- **Hero:** Two-column layout (text left, preview image right)
- **Navigation:** Simplified sticky header (Demo, Status, FAQ)
- **Gallery:** Automatic full-width carousel with infinite loop animation
- **Market Data:** TradingView ticker tape + Polymarket ticker at top AND bottom
- **Status Section:** Visual uptime display with 7-day bar chart
- **FAQ:** Collapsible details elements
- **Unique Elements:** Continuous image carousel, dual market ticker placement

**Best For:** Users who want real-time market context and dynamic image presentation

---

### **Version 3: Clean & Modern (Logo Inline)**
**File:** `3.html`

**Style:** Nearly identical to Version 2, with layout variation

**Key Features:**
- **Hero:** Logo placed inline next to title text (horizontal arrangement) instead of above
- **All other features identical to Version 2**
- **Market Data:** TradingView + Polymarket at top and bottom
- **Gallery:** Same auto-carousel implementation
- **Status & FAQ:** Same as Version 2

**Best For:** Users who prefer the logo integrated horizontally with the title

---

### **Version 4: Bento Grid**
**File:** `4.html`

**Style:** Modern card-based layout with bento grid design

**Key Features:**
- **Hero:** Background image grid (3x3 on desktop, 2x3 on mobile) with dark overlay and centered content
- **Navigation:** Enhanced hover transitions on nav links
- **Gallery/Showcase:** Bento grid layout with varying card sizes (2-column spans, square cards, wide cards)
- **Animations:** Hover scale + shadow effects on cards (translateY + glow)
- **Market Data:** TradingView + Polymarket at top and bottom
- **Status:** Animated pulse indicator with uptime visualization
- **Unique Elements:** Asymmetric card layouts, integrated image/text combinations in cards

**Best For:** Users who want a modern, Pinterest-style layout with visual hierarchy

---

### **Version 5: Sidebar Layout**
**File:** `5.html`

**Style:** Split-screen design with fixed sidebar

**Key Features:**
- **Layout:** Fixed left sidebar (30% width, max 420px) with scrollable right content area
- **Sidebar Contents:**
  - Logo and branding
  - Navigation menu
  - Static market prices (BTC, ETH, S&P 500)
  - "Watch Live" CTA button
  - Footer
- **Hero:** Full-screen background carousel animation with dark gradient overlay
- **Gallery:** 3x2 hover-scale grid
- **Features:** 2x2 grid with icon badges
- **Animations:** Carousel rotation, fade-in on scroll (intersection observer)
- **Unique Elements:** Persistent sidebar navigation, integrated market prices in sidebar

**Best For:** Users who want easy navigation access and app-like experience

---

### **Version 6: Floating Glassmorphism**
**File:** `6.html`

**Style:** Futuristic design with glassmorphic UI elements and animations

**Key Features:**
- **Background:** Animated gradient background (15s shift animation)
- **Header:** Floating glass card header (top center, rounded)
- **Market Data:** Floating glass ticker (below header)
- **Hero:** Centered layout with floating logo (slow float animation)
- **Visual Effects:**
  - Glassmorphism (backdrop-filter blur)
  - Glow effects on key elements
  - Floating animations (slow/medium/fast variations)
  - Hover scale on all cards
- **Features:** 2x2 grid with glowing icon badges
- **Gallery:** 3x2 grid with individual float animations
- **Status:** Glass card with pulsing indicator and glowing status badges
- **Unique Elements:** All sections use glass-heavy styling, multiple animation speeds

**Best For:** Users who want a modern, eye-catching design with depth and motion

---

### **Version 7: Minimalist**
**File:** `7.html`

**Style:** Ultra-clean minimalist design with typography focus

**Key Features:**
- **Hero:** Full-screen video background with massive typography ("Stonk Wars" split across 2 lines)
- **Typography:** Large, bold headings (5xl to 9xl) with light body text, minimal letter spacing
- **Header:** Minimal fixed header with single "Watch" link
- **Market Data:** Compact TradingView ticker (36px height, 3 symbols only)
- **Layout:** Maximum whitespace, clean line-based feature sections
- **Features:** Left-bordered feature list (vertical lava line)
- **Gallery:** Asymmetric layout (1 full-width + 2-column + 3-column rows)
- **Status:** Minimal border-based design
- **FAQ:** Simple border-bottom dividers
- **Animations:** Subtle fade-in on scroll only
- **Unique Elements:** Underline animation on links, dramatic typography, video hero

**Best For:** Users who want a sophisticated, content-focused experience with maximum readability

---

## Common Elements Across All Versions

All versions share these core features:
- **Tailwind CSS** via CDN
- **Color Palette:** Lava orange (#ff4e1b), dark steel background, surface grays
- **Core Content:** About section, features (Real-time Market Data, Chat Interaction, AI Characters, Token Dynamics), status section, FAQ
- **CTA:** Links to pump.fun for live viewing
- **Responsive Design:** Mobile-friendly layouts
- **Media Assets:** Same set of images (1.png through 6.png) and video (stonks1.mp4)

---

## Quick Selection Guide

**Choose Version 1** if you want: Traditional landing page with video focus
**Choose Version 2/3** if you want: Clean modern design with live market data
**Choose Version 4** if you want: Visual interest with bento grid cards
**Choose Version 5** if you want: App-like sidebar navigation
**Choose Version 6** if you want: Eye-catching glassmorphic design
**Choose Version 7** if you want: Minimalist, typography-driven elegance

---

## Technical Details

- **Framework:** Vanilla HTML/CSS/JS (no build process)
- **Styling:** Tailwind CSS via CDN
- **Market Data:** TradingView ticker widget, Polymarket iframe embeds (versions 2-6)
- **Browser Support:** Modern browsers (Chrome, Firefox, Safari, Edge)
- **Performance:** Lightweight (<15KB HTML), CDN assets

---

## Next Steps

The final version will cherry-pick the best features from these prototypes:
- Most effective hero presentation
- Optimal market data integration
- Best gallery/showcase layout
- Most engaging animations
- Cleanest navigation pattern

This README will be updated once the final version is created.
