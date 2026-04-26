# EtchDirect.de - German Chemical Etching Website Specification

## Overview
German-language version of Trade Etching Direct UK website for chemical etching services B2B. Built to match source styling from https://merlindog1.github.io/tradeetching-fullclone/www.tradeetching.com/

## Design Requirements (Matched to Source)

### Color Scheme
- **Black background sections**: `rgb(0, 0, 0)` / `#000000`
- **White text**: `rgb(255, 255, 255)` / `#FFFFFF`
- **Accent blue**: `rgb(7, 153, 226)` / `#0799E2` (used for "T.E.D." brand color)
- **Grey dividers**: `border: 2px solid grey`
- **Body text on light bg**: `rgb(51, 51, 51)` / `#333333`

### Typography
- **Headings**: Montserrat Bold (Google Fonts)
- **Body text**: Comfortaa (Google Fonts) with Montserrat fallback
- **Font sizes**: 36px hero, 23px section headings, 15-16px body

## Page Structure

### Navigation
- Desktop: Horizontal bar with black background, white text, pipe separators "|"
- Menu items: HOME | SERVICES (dropdown) | ARCHITECTURAL | LETTERS | CONCEPTS | INDUSTRIAL | GALLERY | CONTACT
- Dropdown for SERVICES: CHEMICAL ETCHING | CHEMICAL MILLING | METAL PATINATION
- Mobile: Hamburger menu with full-screen overlay

### Layout Sections (in order)
1. **Top bar** (mobile only): "IHR HANDELSPARTNER FÜR CHEMISCHES ÄTZEN – AUSSCHLIESSLICH FÜR DEN FACHHANDEL"
2. **Hero section**: Full-width background image with overlay text
3. **Contact section**: Side by side - left = company info, right = contact form
4. **Features section**: Image on one side, text on other
5. **Benefits section**: "Wie ein eigener Ätzbereich" with bullet points (◈ markers)
6. **Capabilities section**: "Die deutschen Experten für chemisches Ätzen"
7. **Footer**: Black bg, white text, copyright, contact details

## Pages Built
1. **index.html** - Homepage
2. **services/chemical-etching.html** - Chemical Etching service
3. **services/chemical-milling.html** - Chemical Milling service
4. **services/metal-patination.html** - Metal Patination service
5. **architectural.html** - Architectural applications
6. **letters.html** - Letter/lettering services
7. **concepts.html** - Design concepts
8. **industrial.html** - Industrial applications
9. **gallery.html** - Photo gallery
10. **contact.html** - Contact form and information

## Contact Information
- Email: info@etchdirect.de
- Phone: +49 89 12345678
- Address: 1 Industriestraße, 80331 München

## Technical Stack
- Pure HTML5/CSS3 (no frameworks)
- Single CSS file (styles.css)
- Vanilla JavaScript for mobile menu
- Google Fonts: Montserrat, Comfortaa
- Responsive design with mobile-first approach

## Build Date
2026-04-26
