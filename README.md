# Saffron Table

A restaurant management system that runs entirely in the browser. One HTML file, no build step, no backend.

## What it does

- **Dashboard**: sales today, order count, average bill, occupancy, hourly sales chart, top sellers, category split, open orders and stock alerts.
- **New order**: dish grid with search and category filters, cart with table choice, discount and 5% GST.
- **Kitchen board**: tickets move from new to preparing to ready to served. Tickets older than 15 minutes turn red.
- **Floor plan**: 12 tables with seated, reserved and "wants the bill" states, and billing by UPI, card or cash.
- **Reservations**: bookings that fit the party size and block double-booking.
- **Menu**: add, edit, delete or switch off dishes, with cost and margin per dish.
- **Stock**: ordering a dish uses up its ingredients, and dishes show as sold out when one runs short.
- **Reports**: 7-day sales, payment split, category split and best sellers.

Light and dark themes, phone-friendly layout, dish artwork drawn in SVG (no image files).

## Run it

Open `index.html` in any modern browser. No install needed.

## Data

Sample orders, tables and bookings are generated on first load. Everything you change is saved in the browser's `localStorage`. To reset to the sample data, clear the site data for the page.

## Publish with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. The site goes live at `https://<your-username>.github.io/<repo-name>/` after a minute or two.
