# The Raymur Guest Guide

This project is a bespoke, mobile-first digital guest guide and its printable counterpart for **The Raymur**, a boutique-style Airbnb residence in Vancouver, BC.

## Project Overview
The guide provides guests with essential stay information, house rules, local recommendations, and emergency procedures. It is designed with a "boutique hotel editorial" aesthetic.

- **Primary Technologies:** HTML5, CSS3 (Vanilla), JavaScript (for simple interactions and QR generation).
- **Hosting:** Deployed on **Netlify** at [vrtheraymur-guide.netlify.app](https://vrtheraymur-guide.netlify.app).
- **Source Control:** Managed via GitHub at [rtwasser/Netlify-Airbnb-Web-App](https://github.com/rtwasser/Netlify-Airbnb-Web-App).

## Key Files
- `index.html`: The main digital web app. Mobile-first, featuring a photo gallery, interactive map links, and expandable sections.
- `print.html`: A specialized version optimized for Letter-sized (8.5"x11") printing. Includes a dynamically generated QR code pointing to the digital guide.
- `netlify.toml`: Configuration for Netlify deployment.
- `ROBANDVINA-469.jpg`: The primary host photo used in the welcome sections.

## Deployment
This is a static site with no build step required.
- **Manual Deploy:** Use `netlify deploy --prod --dir=.`
- **Continuous Deployment:** Pushing to the `main` branch on GitHub automatically triggers a Netlify build and deploy.

## Development Conventions

### Aesthetic & Styling
- **Fonts:** `Cormorant Garamond` (Serif for headers) and `DM Sans` (Sans-serif for body).
- **Color Palette:** 
  - Cream (`#FAF9F6`)
  - Terracotta (`#C05A3E`)
  - Charcoal (`#2D2D2D`)
- **Tone:** Direct, professional, and welcoming.

### Critical Information & Spelling
- **Spelling:** Always use **Raymur** (not Raymer) and **Vina** (not Veena).
- **Address:** Unit 303, 983 East Hastings St, Vancouver, BC.
- **Door Security:** The front door **does not close naturally**. It is critical to mention that guests must firmly push or pull the door shut.
- **Lost Fob Charges:** Replacement fee is **$50 for a small fob** or **$100 for a garage key fob**.

### Local Recommendations
The guide currently features 18 curated locations. When adding new ones, prioritize Google Maps search links with the specific address included in the query for guest convenience.
