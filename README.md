# OfferTrack Pro – Demo Affiliate Platform

A self-contained demo of an affiliate dashboard similar to iMonetizeIt / CrackRevenue style platforms.

## Features
- User signup & login (stored in browser localStorage)
- Browse offers
- Request unique tracking links
- Copy tracking links
- Simulate clicks + conversions
- Statistics dashboard:
  - Clicks, revenue, EPC
  - Breakdown by country
  - Daily stats
  - Period filters (7 / 30 / 90 / 365 days)

## How to run
1. Open `index.html` in any modern browser.
2. Sign up with any email/password.
3. Go to Offers → Request Link.
4. Copy the link or click “Simulate Click”.
5. Check Statistics and Dashboard.

All data stays in your browser (localStorage). Clear site data to reset.

## Notes
This is a **frontend demo only**. A real production system needs:
- Backend (Node, Python, etc.) + database
- Proper click tracking server
- Postback / S2S conversion tracking
- Fraud detection
- Payment processing
- Legal compliance & terms

You can extend this code or use it as a UI reference.
