# Savoria — Restaurant Dashboard

A restaurant management dashboard UI built for a client. This public version runs on **dummy data**: the client's real figures, orders and names are confidential, so every number, name and order here is placeholder data. The design, components and interactions match the delivered product.

## Screens

- **Overview**: revenue, today's sales, branch performance, profit vs food cost chart, ingredient budget, payment cards, recent orders
- **Orders**: live kitchen board (New → Cooking → Served), orders by channel, peak hours
- **Menu**: dishes with category filter, search, availability toggles, add / edit / delete
- **Reservations**: interactive floor plan, tonight's guest list, new bookings
- **Staff**: team table with shift status, coverage heatmap, top performers
- **Reports**: revenue trend (week / month / year), sales by category, branch targets, CSV export
- **Messages**: supplier, staff and guest conversations
- **Invoices**: supplier bills, pay / view / export
- **Inventory**: stock levels against par, reorder flow, low-stock alerts
- **Settings**: restaurant profile and logo, preferences, opening hours

Light and dark mode, Pakistani Rupee amounts (Rs, Lakh, Crore), keyboard shortcuts (`1`–`6` switch tabs, `N` new order, `/` search) and a simulated live order feed.

## Tech

A single `index.html` with plain HTML, CSS and JavaScript. No build step and no dependencies apart from Google Fonts.
