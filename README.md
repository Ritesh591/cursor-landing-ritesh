# Cursor Landing Page

A single-page marketing landing page for **Cursor** — the AI-powered code editor. Built with vanilla HTML and CSS, this project showcases Cursor's product features, testimonials from industry leaders, and key product updates in a clean, modern dark-themed design.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Features](#features)
- [Design System](#design-system)
- [Sections Breakdown](#sections-breakdown)
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [Asset Organization](#asset-organization)

---

## Overview

This landing page is a pixel-accurate recreation of the Cursor product marketing page, designed to:

- Introduce Cursor as the best way to code with AI
- Build trust through testimonials from notable tech leaders
- Highlight key product capabilities (Agents, Tab autocomplete, multi-surface support)
- Drive conversions with clear call-to-action buttons
- Provide easy navigation to product, resources, and company information

---

## Project Structure

```
cursor-landing-ritesh/
├── index.html          # Main HTML structure (538 lines)
├── style.css           # All styles and layout (728 lines)
├── README.md           # Project documentation
└── assets/
    ├── favicon.ico     # Browser tab icon
    ├── logo.svg        # Cursor logo
    ├── hero-img.png    # Hero section illustration
    ├── join-team.webp  # Join us section image
    ├── arrow.svg       # Link/CTA arrow icon
    ├── download.svg    # Download button icon
    ├── language.svg    # Language selector icon
    ├── light.svg       # Light theme icon
    ├── dask.svg        # Dark theme icon
    ├── system.svg      # System theme icon
    ├── down.svg        # Dropdown chevron icon
    ├── feature/        # Feature section images
    │   ├── feature-1.png
    │   ├── feature-2.png
    │   └── feature-3.png
    ├── frontier/       # Frontier section images
    │   ├── frontier-1.png
    │   ├── frontier-2.png
    │   └── frontier-3.png
    ├── testimonials/   # Testimonial avatars (WebP format)
    │   ├── andrej.webp
    │   ├── diana.webp
    │   ├── greg.webp
    │   ├── jensen.webp
    │   ├── patrick.webp
    │   └── shadcn.webp
    └── trusted-logos/  # Company logos for "Trusted by" section
        ├── adob.svg
        ├── data-dog.svg
        ├── figma.svg
        ├── linear.svg
        ├── nvidia.svg
        ├── open-ai.svg
        ├── ramp.svg
        └── stripe.svg
```

---

## Features

- **Zero dependencies** — Pure HTML and CSS, no JavaScript frameworks
- **Responsive layout** — Flexible grid-based design with max-width containers
- **Sticky navigation** — Navigation bar stays fixed at top on scroll
- **Dark theme** — Professional dark color scheme with CSS custom properties
- **Semantic HTML** — Proper use of `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- **Accessible** — ARIA labels on interactive elements (e.g., theme toggle)
- **Optimized assets** — WebP for photos, SVG for icons and logos

---

## Design System

### Color Palette

| Variable | Hex/OKLab | Usage |
|----------|-----------|-------|
| `--white-color` | `#edecec` | Primary text, buttons |
| `--black-color` | `#14120b` | Background |
| `--gray-color` | `#3a3832` | Borders |
| `--dark-gray-color` | `#1b1913` | Card backgrounds |
| `--light-gray-color` | `#d7d6d5` | Button hover |
| `--description-color` | `#edecec99` | Secondary text (99 = 60% opacity) |
| `--link-color` | OKLab coral/red | Links, CTAs |
| `--link-hover-color` | OKLab 75% opacity | Link hover state |
| `--hover-color` | OKLab 75% opacity | General hover states |

### Typography

- **Font stack:** `"Cursor Gothic", "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif`
- **Font sizes:** 14px (body/links), 16px (descriptions), 22px (card titles), 26px (section titles), 36px (testimonials), 72px (hero CTA)

### Layout

- **Max container width:** 1300px
- **Spacing:** Consistent use of 22px, 56px, 67px, 111px for section padding
- **Border radius:** 4px (images), 16px (buttons), 24px (CTA), 999px (pill buttons)

---

## Sections Breakdown

### 1. Top Navigation Bar
- Cursor logo
- Menu links: Product, Enterprise, Pricing, Resources
- Sign in (outlined) and Download (filled) buttons
- Sticky positioning with `z-index: 100`

### 2. Hero Section
- Headline: *"Built to make you extraordinarily productive, Cursor is the best way to code with AI."*
- Primary CTA: "Download for Linux"
- Hero illustration image

### 3. Trusted By
- Tagline: *"Trusted every day by teams that build world-class software"*
- 8 company logos in a flex row: Stripe, OpenAI, Linear, DataDog, NVIDIA, Figma, Ramp, Adobe

### 4. Feature Sections (3 blocks)
- **Agents** — Turn ideas into code; link to agentic development
- **Tab** — Magically accurate autocomplete; link to Tab
- **Surfaces** — In every tool, at every step; link to Cursor's surfaces

Each card alternates content/image layout (left-right-left).

### 5. Testimonials
- Section title: *"The new way to build software."*
- 6 testimonial cards in a 3-column grid
- Quotes from: Diana Hu (YC), Jensen Huang (NVIDIA), Andrej Karpathy (Eureka Labs), Patrick Collison (Stripe), shadcn (shadcn/ui), Greg Brockman (OpenAI)

### 6. Frontier Section
- Title: *"Stay on the frontier"*
- 3 cards: Best model for every task, Codebase understanding, Develop enduring software
- Each with image, description, and explore link

### 7. Changelog
- 4 changelog cards (versions 2.4, 2.3, plus dated entries)
- Highlights: Subagents, Skills, Image Generation, CLI Agent Modes, Layout Customization, etc.
- Footer link: "See what's new in Cursor"

### 8. Join Us
- Card with headline about Cursor's applied research team
- "Join us" CTA link
- Team collaboration image

### 9. Recent Highlights
- 3 blog-style cards:
  - Cursor 2.0 and Composer
  - Improving Cursor Tab with online RL
  - 1.5x faster MoE training with custom MXFP8 kernels
- "View more posts" link

### 10. Try Cursor Now
- Large headline: *"Try Cursor now"*
- Download for Linux CTA button

### 11. Footer
- 5 columns: Product, Resources, Company, Legal, Connect
- Copyright: © 2026 Anysphere, Inc. · SOC 2 Certified
- Theme toggle (System / Light / Dark)
- Language selector (English)

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or package managers required

### Running the Project

1. **Clone or download** the project folder.

2. **Open in browser:**
   - Option A: Double-click `index.html` to open in your default browser
   - Option B: Use a local server (recommended for accurate path resolution):
     ```bash
     # Using Python 3
     python -m http.server 8000

     # Using Node.js (npx)
     npx serve .
     ```
   - Navigate to `http://localhost:8000` (or the port shown)

3. **No installation** — The project runs entirely in the browser with no dependencies.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure, accessibility |
| **CSS3** | Layout (Flexbox, Grid), custom properties, transitions |
| **SVG** | Icons, logos (scalable, lightweight) |
| **WebP** | Optimized images for testimonials |
| **PNG** | Feature and frontier illustrations |

---

## Asset Organization

- **Icons:** Root-level SVGs for UI elements (arrow, download, theme, language)
- **Feature images:** `assets/feature/` — Screenshots for product features
- **Frontier images:** `assets/frontier/` — Product capability visuals
- **Testimonials:** `assets/testimonials/` — WebP avatars for performance
- **Trusted logos:** `assets/trusted-logos/` — SVG logos of partner companies

---

## License

This project is a personal/educational recreation of the Cursor marketing page. Cursor, its branding, and related assets are trademarks of Anysphere, Inc.

---

*Built with attention to detail for a clean, professional landing page experience.*
