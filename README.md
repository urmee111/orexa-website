# OREXA — Website

A frontend build for OREXA, a men's formal wear e-commerce brand (Bangladesh).
Petrol green + matte gold branding, built page by page in plain HTML/CSS/JS.

## Status

This is a **frontend-only** build right now — no backend, no database, no
real cart/checkout. All product data, photos, and offer details are
**placeholders** until the client provides real content.

## Pages

| File | What it is |
|---|---|
| `index.html` | Homepage — hero slider, categories, new arrivals, all products |
| `product.html` | Product detail page (currently: Ivory Twill Formal Shirt) |
| `shirts.html` / `tshirts.html` / `panjabi.html` / `trousers.html` | Category listing pages |
| `offers.html` | Ongoing offers with terms & conditions |
| `discounts.html` | %OFF — discounted items |
| `combo.html` | Combo deals |
| `reviews.html` | Customer review screenshots |
| `profile.html` | Credit/profile page — **design mockup only, not functional** |

## Design system

- **Colors** (CSS variables in `style.css`):
  - Petrol Green `#0D3B3E` — main text/structure
  - Active Green `#095051` — hover/active states
  - Off-White `#F7F7F3` — background
  - Matte Gold `#D4AF37` — primary CTA buttons only, used sparingly
- **Fonts**: Fraunces (headlines), Satoshi (body/UI)
- Sharp, minimal style — no gradients, no drop shadows, no all-caps labels

## Running locally

Open the project folder in VS Code, right-click any `.html` file →
"Open with Live Server".

## Known placeholders (need real data from client)

- [ ] Real WhatsApp business number (currently `8801XXXXXXXXX` — appears in
      footer + product/profile pages)
- [ ] Real product photos (currently grey placeholder boxes)
- [ ] Full product catalog — real names, prices, descriptions
- [ ] Real offer terms and validity dates
- [ ] Real customer review screenshots
- [ ] Client's original "category style" reference image not yet applied

## Not built yet

- Backend + database for the Credit system (pending client decision — see
  the note on `profile.html`)
- Individual product pages for items other than Ivory Twill Formal Shirt