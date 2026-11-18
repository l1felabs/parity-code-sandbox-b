# parity-code-sandbox

A small shop app (Node 20+, CommonJS, no dependencies): money in cents, items, discounts, state tax, coupons, inventory with reservations, orders, a daily report, JSON storage, a tiny HTTP server (`/healthz`, `/quote`) and a CLI.

Test sandbox only, for side-by-side coding-agent runs. Not a product; holds no secrets. `npm test` runs the suite (node:test). CI: `cloudbuild.yaml` runs `npm test` on Google Cloud Build.

