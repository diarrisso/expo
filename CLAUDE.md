# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML mockup project for **Toni Janis Garten- und Landschaftsbau** (landscaping and gardening business) in Delmenhorst, Germany. The project contains design mockups, specifications, and templates that serve as the foundation for a future WordPress website implementation.

## Project Type

Static HTML/CSS demo repository - NOT a WordPress installation. These files are mockups to guide the future WordPress development.

## File Structure

```
demo/
├── index.html                          # Main homepage mockup (latest version)
├── toni-janis-website-mockup.html      # Alternative homepage design
├── toni-janis-flyer-template.html      # Print flyer template
├── toni-janis-wordpress-specs.md       # Complete technical specifications
└── README.md                           # Project readme
```

## Key Files

### index.html
The primary homepage mockup with full implementation of the design system. This is the most up-to-date version and should be used as the reference for all design elements.

### toni-janis-wordpress-specs.md
Complete technical specifications document containing:
- Color palette and CSS variables
- Typography specifications (Playfair Display + Source Sans 3)
- Recommended WordPress themes and plugins
- Site structure and navigation
- Component styling (buttons, cards, spacing)
- Contact information
- SEO keywords and meta tags
- DSGVO compliance checklist
- Hosting recommendations

## Design System

### Color Palette (Kiwi Green Theme)
The project uses a modern green color scheme centered around kiwi/lime green tones:

```css
--kiwi-green: #8BC34A;      /* Primary brand color */
--kiwi-dark: #689F38;       /* Darker variant */
--kiwi-light: #AED581;      /* Light variant */
--kiwi-accent: #9CCC65;     /* Accent color */
--earth-brown: #5D4037;     /* Text color */
--sand-beige: #E8E0D5;      /* Background variant */
--cream: #FAF8F5;           /* Main background */
--charcoal: #2D2D2D;        /* Dark text */
```

Note: Early specs referenced "Forest Green" (#2E5A3C), but the implemented design uses the kiwi green palette shown above. The HTML files use CSS variables with both naming conventions for compatibility.

### Typography
- Headers: Playfair Display (400, 600, 700)
- Body/UI: Source Sans 3 (300, 400, 500, 600)
- Fonts loaded via Google Fonts CDN

### Design Principles
- Mobile-first responsive design
- Smooth animations and transitions
- Natural/organic aesthetic with decorative leaf elements
- Professional landscaping business look
- Emphasis on trust and craftsmanship

## Business Information

```
Company: Toni Janis Garten- und Landschaftsbau
Address: Düsternort Str. 104, 27755 Delmenhorst
Phone 1: 0176 343 26549
Phone 2: 0176 878 29995
Email: toni-janis@hotmail.com
WhatsApp: wa.me/4917634326549
```

## Planned Services
- Gartengestaltung (Garden design)
- Gartenpflege (Garden maintenance)
- Pflasterarbeiten (Paving work)
- Rollrasen verlegen (Lawn installation)
- Zaunbau (Fence construction)
- Winterdienst (Winter services)

## Language

All content is in German (Deutsch) for the German market. When modifying or creating content, maintain German language throughout.

## Viewing the Mockups

Open any HTML file directly in a browser. No build process or server required.

```bash
# macOS
open index.html

# Or start a simple server
python3 -m http.server 8000
```

## WordPress Implementation Notes

This repository is for mockup/demo purposes. When implementing in WordPress:

1. Use Astra, Kadence, or similar lightweight theme
2. Implement color palette via theme customizer or custom CSS
3. Load Google Fonts: Playfair Display + Source Sans 3
4. Essential plugins: Elementor/Page Builder, Contact Form, Yoast SEO, LiteSpeed Cache
5. Ensure DSGVO compliance (Cookie banner, privacy policy, impressum)
6. Set up Google My Business for local SEO
7. Configure structured data for LocalBusiness schema

Refer to `toni-janis-wordpress-specs.md` for complete implementation guidelines.

## SEO Strategy

Target keywords focused on local services in Delmenhorst area:
- Garten- und Landschaftsbau Delmenhorst
- Gartengestaltung Delmenhorst
- Pflasterarbeiten Delmenhorst
- Rollrasen verlegen Bremen

Local SEO emphasis with Google My Business integration.
