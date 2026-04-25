# SQL Weekend

A two-day SQL intensive. Runs entirely in the browser — no install, no setup, no backend. Real SQLite database via [sql.js](https://github.com/sql-js/sql.js), ten lessons with exercises, and progress that persists in `localStorage`.

## Contents

- **Saturday — Foundations.** SELECT, WHERE, ORDER BY, GROUP BY, JOINs.
- **Sunday — Advanced.** Subqueries, CTEs, window functions, data modification, final challenges.

## Running it

Any of these work:

- **Hosted (GitHub Pages):** visit the deployed URL.
- **Local:** clone the repo and open `index.html` directly in a browser. No build step.
- **Dev server (optional):** `python3 -m http.server` from the repo root, then open `localhost:8000`.

## The dataset

A small online retailer. Five tables:

- `customers` — 30 rows across a dozen countries
- `products` — 32 items across Electronics, Books, Apparel, Pantry, Home, Stationery
- `orders` — 40 orders with dates and statuses
- `order_items` — line items linking orders to products
- `employees` — 10 rows with a manager hierarchy (for recursive CTE practice)

Schema details are available in-app via the floating **Schema ↗** button.

## Credits

Database engine: [sql.js](https://github.com/sql-js/sql.js). Typography: Fraunces and JetBrains Mono via Google Fonts.
