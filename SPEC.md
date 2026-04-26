# EtchDirect.de - German Chemical Etching Website Specification

## Overview
German-language version of Trade Etching Direct UK website for chemical etching services B2B.

## Color Palette
Based on source site analysis:
- Primary Dark: `#000000` (black backgrounds)
- Primary Light: `#FFFFFF` (white text/backgrounds)
- Accent Blue: `#0799E2` (T.E.D. brand color)
- Grey Text: `#666666` / `rgb(102, 102, 102)`
- Gold/Amber: `#D4AF37` (accent highlights)
- Dark Gold: `#B8860B` (hover states)

## Typography
- Primary Font: Montserrat (via Google Fonts)
- Fallback: Arial, sans-serif
- Headings: Bold, varying sizes (36px hero, 24px section titles, 16-20px body)
- Body: 15-16px regular

## Page Structure
1. **Homepage (index.html)** - Hero, about, features, contact CTA
2. **Chemical Etching (services/chemical-etching.html)** - Service detail
3. **Chemical Milling (services/chemical-milling.html)** - Service detail
4. **Metal Patination (services/metal-patination.html)** - Service detail
5. **Architectural (architectural.html)** - Architectural applications
6. **Letters (letters.html)** - Letter/lettering services
7. **Concepts (concepts.html)** - Design concepts
8. **Industrial (industrial.html)** - Industrial applications
9. **Gallery (gallery.html)** - Photo gallery
10. **Contact (contact.html)** - Contact form and information

## Navigation
- Desktop: Horizontal nav with dropdown for Services
- Mobile: Hamburger menu with full-screen overlay
- Links: HOME | SERVICES (dropdown) | ARCHITECTURAL | LETTERS | CONCEPTS | INDUSTRIAL | GALLERY | CONTACT

## Contact Information
- Email: info@etchdirect.de
- Phone: +49 89 12345678
- Address: 1 Industriestraße, 80331 München

## SEO Requirements
- HTML lang="de"
- German title tags (max 60 chars)
- German meta descriptions (max 160 chars)
- German alt attributes for all images
- Semantic HTML5 structure

## Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## Technical Stack
- Pure HTML5/CSS3 (no frameworks)
- Single CSS file (styles.css)
- Vanilla JavaScript for mobile menu
- Google Fonts via CDN
