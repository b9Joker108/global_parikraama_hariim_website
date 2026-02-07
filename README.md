# Global Parikrama Harīm website

An uncluttered, ready-to-edit single-page template for the Global Parikrama Harīm journey.

## How to use
1. Open `index.html` in your browser to preview the page locally.
2. Edit text directly in `index.html` (hero, highlights, itinerary, logistics, FAQ, and contact CTAs).
3. Update links by changing the `href` values on the buttons (email/WhatsApp/registration).
4. Adjust the palette once in `styles.css` by editing the CSS variables at the top (`--accent`, `--bg`, etc.).
5. Duplicate or remove cards:
   - Highlights: copy/paste an `<article class="card">...</article>`.
   - Itinerary: copy/paste a `<div class="itinerary-step">...</div>`.
   - FAQ: copy/paste an `<article class="faq-item">...</article>`.
6. Optional imagery: set a background image on `.hero` in `styles.css` or add `<img>` tags inside any card.

## Quick serve
Run a simple server to preview:
```bash
python -m http.server 8000
# then open http://localhost:8000 in your browser
```
