# First Assignment

Simple product listing web project that fetches data from DummyJSON and displays product cards with pagination, search suggestions, and product detail pages.

Files
- `index.html` — main listing page
- `product.html` — product detail page
- `search.html` — search results page
- `script.js` — main JavaScript (fetch, pagination, search suggestions)
- `product.js` — product detail logic
- `search.js` — search results logic
- `style.css` — styles (simple, improved UI)
- `history.html`, `history.js` — visit/search history

Key Notes
- Pagination shows 6 items per page (configured in `script.js` via `itemsPerPage = 6`).
- Data is fetched from `https://dummyjson.com/products` — an active internet connection is required.
- Styling improved using only basic CSS (see `style.css`).

Run locally
1. Quick (no server): open `index.html` in your browser. Some browsers restrict fetch from local files, so a local server is recommended.
2. Start a simple Python HTTP server (recommended):

```bash
python -m http.server 8000
```

Then open: http://localhost:8000/index.html

Testing
- Verify 6 product cards per page and pagination buttons at the bottom.
- Try the search box; saved queries appear in suggestions (localStorage).
- Click a product card to open its detail page (visit saved to localStorage).

Development
- Edit `style.css` to tweak UI colors/spacing.
- Edit `itemsPerPage` in `script.js` to change how many items display per page.

License
- No license specified.
