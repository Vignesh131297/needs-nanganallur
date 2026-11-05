# Needs Supermarket, Nanganallur

Website for **Needs Supermarket**, 43/31, 1st Main Road, Ram Nagar, Nanganallur, Chennai 600061.
"Your one-stop shop for all home needs." Instagram: [@needs__supermarket](https://www.instagram.com/needs__supermarket/)

A single static page (`index.html`), bilingual in English and Tamil, in the shop's own colours: the dark wood facade, the blue script sign, the red rose and the yellow logo disc.

## What's on the page

- Intro: the blue "Needs" sign lights up and the rose blooms, once per visit
- Hero notepad that writes a Saturday list and ticks it off
- Scroll story: the yellow Needs bag fills with a week of shopping
- Ten sections of drawn items (cookware, brass and pooja, gifts and toys, stationery, personal care, home decor, electronics, pet supplies, fashion and textiles, special days) with a brand and size picker, plus search
- "My list" that sends the order to the shop on WhatsApp
- This week's finds as hanging price tags, a reels section linking to Instagram and YouTube
- Special days shelf with a kolam that draws itself
- Illustrated storefront, address, hours, phone and a customer review
- Mobile action bar (Call, Shop, My list)

## Before going live

| What | Where | Status |
| --- | --- | --- |
| WhatsApp number | `const WHATSAPP = "919840297100"` | Shop phone from Google Maps. Confirm it takes WhatsApp |
| Phone | `tel:+919840297100`, `098402 97100` | From Google Maps |
| Weekly finds and prices | `const OFFERS` | Sample prices |
| Brands stocked | `const AISLES` | Examples, confirm with the shop |
| Logo | `.brand-mark` SVG | Redrawn; swap in the official file |
| Photos | storefront is an illustration | Add the shop's own photos if wanted |

Then remove the "Website concept" line in the footer and the sample-price note.

## Run it

No build step. Open `index.html`, or serve the folder with `npx serve .`. Deploys as-is to GitHub Pages, Netlify or Vercel.
