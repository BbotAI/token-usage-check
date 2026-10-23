# Token Usage Check (NTUI app)

A one-page app that answers in plain English whether Canton Coin (CC) and Chainlink (LINK) are actually used by the systems that make tokenization claims.

- `docs/index.html` is the app, served by GitHub Pages from `/docs`.
- `docs/data.json` holds the numbers. The NTUI Google Sheet (Apps Script) rewrites it every day after its 02:00 UTC run, so the sheet's REPORT tab and this app always show the same data.
- Nothing here is edited by hand. To change the numbers, change the sheet's logic.

Data sources: Lighthouse (third-party copy of Canton Scan), Blockscout, supply.chain.link, Chainlink CCIP API. Not investment advice.
