# Jorge Guerra · Tools Hub

Static landing page for Jorge Guerra’s calculators and simulators
(ForceMetric, Sound Distance Calculator, Gunshot Sound Propagation, …).

## Visit counter (GoatCounter)

GitHub Pages cannot host a server-side counter. This hub uses
[GoatCounter](https://www.goatcounter.com/) — privacy-friendly, no ads,
no tracking cookies.

1. Create a GoatCounter site and note your code (subdomain).
2. Edit `js/goatcounter-config.js`: set `enabled: true` and replace `YOUR-CODE`
   in `endpoint`.
3. Redeploy Pages.

Until configured, the counter stays **inactive** (no fake localStorage counts).

## Deploy

Static files only. GitHub Pages from `main` / `/` (or `docs/`).
