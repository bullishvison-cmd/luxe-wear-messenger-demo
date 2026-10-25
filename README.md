# LUXE WEAR — Messenger Demo

A simulated Facebook Messenger-style chatbot demo for the fictional clothing
brand LUXE WEAR. Built to show clothing businesses how automated replies on
their Facebook Page could answer customer questions.

## What this is

- A single self-contained `index.html` — no build step, no backend, no paid
  APIs, no API keys. Open it in any browser and it works.
- A local, rule-based chatbot: it answers product, size, color, price,
  shipping, tracking, return, discount, payment, and support questions, and
  handles everyday conversation (greetings, thanks, browsing, complaints,
  requests for a human).
- It never goes silent: every message gets a reply, and when information
  isn't configured in the demo it says so honestly instead of guessing.

## What this is NOT

- This is a **simulation**. It is **not connected to Facebook**, a real
  inventory system, an order database, a payment processor, or a shipping
  carrier. Nothing here contacts a real employee or places a real order.
- All business details are fictional sample data: Classic Premium Hoodie,
  $39, sizes S/M/L/XL, colors black/gray/navy, cotton-blend fabric,
  standard US shipping typically 3–5 business days, eligible unworn items
  returnable within 30 days, support hours Monday–Friday 9 AM–5 PM ET.

## Run it

Open `index.html` in a browser. No installation needed.

## Connecting a real Facebook Page later

A live Messenger integration is a separate step and would require a
Facebook Page controlled by the business owner, a Meta developer app with
Messenger Platform permissions, a backend with a public HTTPS webhook, and
secure storage of Page access tokens and app secrets.
