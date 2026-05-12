# SimpleMinima Studio — Website

## File Structure

```
/
├── index.html          ← Home
├── about.html          ← About
├── products.html       ← Products
├── journal.html        ← Journal / Field notes
│
├── images/
│   ├── products/       ← Drop product images here
│   │     poster-001.jpg
│   │     tote-001.jpg
│   │     tee-001.jpg
│   │
│   └── journal/        ← Drop journal images here
│         entry-001.jpg
│         entry-002.jpg
│         ...
│
└── README.md
```

---

## Adding a Product

1. Drop image into `images/products/`
2. Open `products.html`
3. Find a `.product-card` block — copy it
4. Paste it inside the correct `.product-grid`
5. Update:
   - `src="images/products/your-image.jpg"`
   - `.product-tag` — category
   - `.product-title` — name
   - `.product-desc` — description
   - `.product-status` — Available / In Production / Closed / Sold Out
   - `.product-price` — e.g. RM 85 (delete the line if no price yet)

---

## Adding a Journal Entry

1. Drop image into `images/journal/`
2. Open `journal.html`
3. Choose an entry format:
   - **Full width** — big image, long text (featured entry)
   - **Grid card** — two-column, shorter text
   - **Horizontal** — image + text side by side
   - **Observation** — text only, no image
4. Copy the HTML block and paste it below the page header
5. Update image path, date, tag, title, and body text

---

## Deploying to Vercel

1. Push folder to a GitHub repo
2. Import repo at vercel.com
3. No build config needed — static files

---

## Colors (for reference)

| Name       | Hex     | Use                        |
|------------|---------|----------------------------|
| Warm White | #F2EFE9 | Background                 |
| Bone       | #E8E4DC | Hover, subtle surface      |
| Linen      | #D9D3C7 | Borders, rules             |
| Raw Paper  | #C8BFA8 | Inactive status, captions  |
| Clay       | #A0826D | Accent — dates, tags, CTA  |
| Oxide      | #7A5C4F | Available status           |
| Ash        | #6B6862 | Body text, nav links       |
| Graphite   | #2C2B29 | Primary text, headings     |

## Fonts

- Headings: `Instrument Serif` (loaded from Google Fonts)
- Accent headings: `Cormorant Garamond`
- Body + UI: `DM Mono`

All fonts load from Google Fonts CDN — no installation required.
