# Udyami Queens — Seller Hub

A seller dashboard for Udyami Queens, the women-led hyperlocal quick-commerce platform under Udyami Bharat. A Queen Seller uses it to run her home enterprise: products, orders, stock, payouts, customer feedback and registrations.

It is a single file, `index.html`, with no build step and no sample data. Everything shown comes from what the seller enters.

## Run it

Open `index.html` in any browser. Nothing to install.

Where data is saved:

| Opened from | Data is saved to |
|---|---|
| The published claude.ai artifact | The owner's Claude account (same on every device) |
| This file in a browser | That browser only (`localStorage`) |
| A private window | Nowhere; it resets on reload |

## Pages

| Page | What the seller does there |
|---|---|
| Overview | 6-step setup guide, today's sales and orders, live orders, 7-day revenue chart, top sellers, stock alerts, this week's payout, busy-hours heatmap |
| Orders | Records an order, then moves it New → Packing → With rider → Delivered, or cancels it (stock is returned) |
| Catalog | Adds products with price, stock and reorder level; edits prices; hides or deletes products |
| Inventory | Corrects counts, adds fresh batches, sets reorder levels |
| Payouts | Weekly sales minus platform fee, monthly goal progress, marks weeks as received, copies CSV |
| Reviews | Records customer feedback and replies |
| Learn and grow | Tracks Udyam, FSSAI, GST and bank registration, and Mudra, Stand-Up India, PMEGP and PMFME schemes |
| Shop settings | Name, shop, area, platform fee, monthly goal, erase all data |

## Step-by-step setup

1. **Shop settings** — enter your name, shop name, area, platform fee (%) and monthly goal. Save.
2. **Catalog** — add each product with its price, stock ready now and reorder level.
3. **Orders** — when a customer orders, add each item, enter the delivery area and payment type, then Create order.
4. **Deliver** — press Accept, Hand to rider, then Mark delivered. Only delivered orders count as sales.
5. **Payouts** — check the week's payout and press Mark received when the money arrives.
6. **Reviews** — record what customers say and reply.

## Not yet covered (from the BRD)

These requirements from *Udyami Queens BRD — Final Consolidated v3* are not in this version:

- Onboarding questionnaire and Aadhaar / PAN / bank KYC (SEL-01, section 16)
- Inbound-to-hub scheduling with batch and shelf-life capture (SEL-04)
- FCMCSL funding: apply, limit, sales-linked repayment (SEL-06)
- Full order status model with Quality Checked and Ready for Pickup (section 18.1)
- Quality flags and training library (SEL-07)
- Kannada / English toggle (SEL-08)
- Rider, Hub/CP, Admin and Finance dashboards (sections 7.3–7.6, 34.4)
