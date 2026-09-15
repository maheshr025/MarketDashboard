# Market Terminal (PWA)

Live market dashboard using your own FMP API key. Runs on any phone as an installed app.

## Deploy (GitHub Pages)
1. Create a new public repo on GitHub (e.g. `market-terminal`).
2. Upload all files in this folder to the repo root.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. Open `https://<your-user>.github.io/market-terminal/` on your phone.

## Install on phone
- Android (Chrome): menu → "Add to Home screen" / "Install app".
- iPhone (Safari): Share → "Add to Home Screen".

## First run
Tap **API key** (under the watchlist) and paste your FMP key from https://site.financialmodelingprep.com/developer/docs/dashboard. It is stored only in your browser's local storage on that device.

## Symbols
Stocks/ETFs: AAPL, SPY · Crypto: BTCUSD · Forex: EURUSD · Commodities: GCUSD, CLUSD.
Watchlist polls each ticker once a minute; keep it under ~15 names on the Starter plan.
