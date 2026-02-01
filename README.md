<!-- prettier-ignore -->
# 🛍️ My Ecommerce Store — Frontend

A clean, lightweight product listing demo that fetches sample data and displays product cards with pagination, simple search suggestions, and product detail pages.

What you'll find
- `index.html` — Main product listing
- `product.html` — Product details view
- `search.html` — Search results
- `script.js` — Fetch, pagination, and search-suggestion logic
- `product.js`, `search.js` — Page-specific scripts
- `style.css` — Easy-to-edit CSS for layout and visuals
- `history.html`, `history.js` — Saved visit/search history utilities

Highlights
- Pagination is set to show 6 items per page (see `script.js`).
- Product data comes from DummyJSON; the app requires internet access to fetch data.
- Styling uses basic, widely-supported CSS only — easy to customize.

Quick Start

- To preview: open `index.html` in your browser.
- If your browser blocks network requests from local files, run a simple local server (for example, `python -m http.server 8000`) and open the address your server prints.

Testing Checklist
- Confirm six product cards appear per page.
- Use the search box: saved queries appear in suggestions (stored in `localStorage`).
- Click a product card to open its detail page; visit history is stored in `localStorage`.

Development
- Tweak visual styles in `style.css`.
- Change pagination count by editing `itemsPerPage` in `script.js`.

Ideas / Next Enhancements
- Add sorting (price, rating).
- Add a lightweight cart stored in `localStorage`.
- Improve accessibility (keyboard navigation, ARIA labels).

License

No license specified — feel free to adapt this for learning and demo purposes.

---

Enjoy! If you'd like, I can add a short contributor guide or a screenshot section next.
