# Finance Hub

A clickable proof of concept for a company finance dashboard, built to agree on the screens and rules before the MVP.

**Live demo:** https://ahmedhassanfoad.github.io/finance-hub/

All figures are generated sample data. Anything you add is saved only in your own browser (localStorage); use **Reset sample data** in the sidebar to start over.

## What it covers

- **Online sales**: three factories (Blanc, Fourteen, OneOSeven) and four brands (Blanc and Lady Blanc share the Blanc factory).
  - **Suppliers**: per-brand dashboard with six figures (stock received, sold, collections, flyers, returned, shipping), stock flow, a daily sheet for sold/returned/shipping, and a daily report.
  - **Collections**: quick entry by day and brand; every collection goes into the main safe.
  - **Invoices**: a plain daily log with automatic numbering and search.
  - **Account statement (كشف حساب)**: one per factory. Stock received adds to the factory debt and to the brand's stock; payments reduce the factory debt only.
- **Production**: sections (warehouses, printing, course, others) with expenses, collections and stock in/out.
- **Marketing**: money in/out and spend by channel.
- **Safes**: a main safe limited to 10 approved spending categories, and an office safe for petty cash with receipt tracking and a low-balance alert.

## Running it

It is a single self-contained file. Open `index.html` in a browser, no build step or server needed.
