# Shri Chand Treks — Proof of Concept (static site)

This is a **static HTML** proof-of-concept website generated from the itinerary documents you provided.

## Open locally (fastest)
- Double-click `index.html` (works, but some browsers restrict form submissions when opened as a file).
- Recommended: run a tiny local server:

```bash
cd shri-chand-treks-poc
python -m http.server 8000
```

Then open: http://localhost:8000

## Deploy in minutes (recommended for sharing)
### Option A — Netlify (no code)
1. Go to Netlify
2. Drag-and-drop the folder onto the dashboard
3. You get a live URL instantly

### Option B — GitHub Pages
1. Create a new GitHub repo
2. Upload all files
3. Enable Pages in repo settings (deploy from main branch)

## Where to edit content
- Trek data is also exported to `data/treks.json` for reference.
- In this POC, trek pages are pre-generated under `treks/`.

## Next upgrades (production-ready)
- Add a proper fixed-departure **calendar**
- Add **Razorpay** payment links (deposit + full payment)
- Add a lead pipeline (CRM / sheet / Airtable)
- Add **SEO**: custom meta titles, FAQs, schema markup
- Add a **gallery** using your own photos

## Contact form
The contact form points to:
`https://formspree.io/f/your-form-id`

Replace it with your actual Formspree / Netlify form endpoint.
