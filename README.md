# Kinnori Boutique
A responsive, Indian heritage-inspired boutique website built with Vite and vanilla HTML, CSS, and JavaScript.

## Run locally
```sh
npm install
npm run dev
```

## Production
```sh
npm run build
```
Deploy the resulting `dist` directory to a static host. No backend or secrets are required. Asset URLs assume deployment at the root of a domain.

## Features
- Responsive desktop, tablet, and mobile layouts
- Three curated collection edits and category filtering
- Search by collection, colour, and craft keywords
- Favourite edits saved locally on the visitor's device
- Accessible dialogs, keyboard focus trapping, Escape to close
- Collection details and personalised WhatsApp enquiry forms
- Three customer testimonial excerpts from the supplied material
- How-to-order guide, exhibitions information, and genuine contact links
- Self-hosted fonts and images

## Content and imagery
Business details, artisan count, founding year, contact information, and customer review excerpts come from the supplied brief and screenshots. No prices, live stock counts, exhibition dates, or delivery promises have been invented.

The full-width red-saree courtyard hero is AI-generated editorial imagery, labelled on the page. The collection, story, and packaging photographs are the supplied business photos (cropped/resized). The three collection edits are browsing categories, not confirmed in-stock SKUs; details ask visitors to confirm designs and availability with Debadrita.

The logo is a new typographic/lotus design for this website concept, not a reproduction of the supplied circular logo.

## Ordering
There is no checkout, payment processor, live inventory, or order database. Enquiry forms compose a WhatsApp message to +61 478 551 277. The visitor must send the message in WhatsApp. Email and phone links are also available. WhatsApp activation for the supplied number was not independently verified.

## Editing
- `index.html`: page copy and sections
- `style.css`: theme and responsive styles
- `main.js`: collection data, search, favourites, forms, and reviews
- `public/images/`: photography
- `fonts.css` and `public/fonts/`: self-hosted typefaces

## Verification
Browser checks covered filters, favourites and persistence, search and empty states, detail/enquiry dialogs, composed WhatsApp URLs, reviews, order help, event information, mobile navigation, and horizontal overflow at 320, 390, 768, 1024, and 1440 pixel widths. The production build passed.
