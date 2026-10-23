# Nainital Sweets & Restaurant — website demo

A responsive, four-page static website concept by AWEN DIGITALS.

## Pages

- `index.html` — Home
- `menu.html` — Menu categories with working category filters
- `about.html` — About the business, without an invented founding story
- `visit.html` — Address, phone, Instagram, WhatsApp and Google Maps search

## Features

- Mobile-first navigation with an accessible open/close state
- Black, gold and charcoal theme based on the supplied logo screenshot
- Click-to-call, WhatsApp enquiry and map-search links
- No cart, online payment, invented prices, unconfirmed opening hours, fake reviews or ratings
- Illustrative food images are explicitly noted as demo imagery
- Responsive CSS and reduced-motion support
- Basic metadata and page-specific titles/descriptions

## Before presenting it as a live business website

1. Confirm permission to publish the restaurant's logo and contact details.
2. Replace illustrative food imagery with owner-approved photographs when available. Current external image URLs are used only as demo placeholders and require an internet connection.
3. Verify the Google Maps pin and opening hours with the owner. Hours are intentionally omitted.
4. Confirm menu names, current availability, prices and portions with the restaurant. Prices are intentionally omitted.
5. Review all links on a real mobile device and confirm the phone/WhatsApp number.
6. This is a static menu-and-enquiry website only; it does not accept orders or payments.

## Run locally

Open `index.html` in a browser. For a local development server, run in this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to Vercel

Import the folder/repository as a static project in Vercel. No build command is required; publish the project root. If you're replacing files in an existing GitHub-connected Vercel project, back up the previous site first and confirm the repository belongs to this demo before committing.

## Image and logo notes

- `assets/nainital-logo.png` is a circular crop derived from the screenshot the user supplied; obtain the original logo file from the business for production use.
- `assets/logo-crop.png` is an unmasked reference crop of that same screenshot.
- Food imagery is linked from Unsplash image URLs, is illustrative only, and does not depict verified photos of Nainital Sweets & Restaurant.
