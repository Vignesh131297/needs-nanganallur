# V.V. Mart, Nanganallur

Website concept for **V.V. Mart**, the supermarket at 39, 1st Main Road, NCBS Colony, Nanganallur, Chennai 600061.

A single static page (`index.html`), bilingual in English and Tamil, in the shop's own signboard colours.

## What's on the page

- Neon intro: the V.V. Mart sign switches on, once per visit
- Hero notepad that writes a shopping list and ticks it off
- Scroll story: a yellow manjappai fills with a week of shopping
- Eight aisles of drawn items with a brand and size picker, plus search
- "My list" that sends the order to the shop on WhatsApp
- Weekly offers as hanging price tags, festival shelf with a kolam that draws itself
- Full-width storefront, directions, hours and a customer review
- Mobile action bar (Call, Aisles, My list)

## Before going live

Replace the sample values:

| What | Where |
| --- | --- |
| WhatsApp number | `const WHATSAPP = "910000000000"` in the script |
| Phone number | `tel:+910000000000` and `+91 00000 00000` in the page |
| Weekly offers and prices | `const OFFERS` |
| Brands the shop stocks | `const AISLES` |
| Delivery areas | the "We deliver around" list |
| Logo | the emblem is redrawn from a photo; swap in the official file |
| Storefront photo | `assets/storefront.jpg`, a higher-resolution photo will look sharper |

Then remove the "Website concept" line in the footer and the sample-price notes.

## Run it

No build step. Open `index.html`, or serve the folder:

```
npx serve .
```

Deploys as-is to GitHub Pages, Netlify or Vercel.
