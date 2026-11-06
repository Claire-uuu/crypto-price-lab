# Crypto Price Lab — The Price Is Not One Number

An interactive data-journalism **prototype** exploring why a cryptocurrency can have different reported prices across exchanges, and why a single market price can be misleading.

**[Explore the interactive story](https://claire-uuu.github.io/crypto-price-lab/)** (available once GitHub Pages is enabled)

## Current publication status

- The live landing page uses **synthetic, illustrative observations** for BTC, ETH, and SOL. These are **not real market prices**.
- The interface and educational explanations are implemented.
- No historical cross-exchange price findings have been independently verified or published yet.
- The project is an independent portfolio project informed by general lessons from a VortexNet software engineering internship. It does **not** publish employer data or code.

## Editorial question

When two exchanges show different prices for the same asset, are the prices genuinely comparable? A meaningful investigation must align asset pairs, UTC intervals, measurement definitions, and missing-data handling before drawing conclusions.

An hourly candle close is not an executable quote, and a price discrepancy is not evidence of arbitrage.

## Planned evidence-backed upgrade

1. Collect publicly accessible BTC/USD hourly OHLC data from Coinbase and Kraken.
2. Archive raw source responses, retrieval times, API parameters, and SHA-256 checksums.
3. Validate UTC alignment, duplicate timestamps, missing intervals, incomplete candles, and invalid prices.
4. Calculate matched-hour closing-price differences in basis points and report coverage, median, 95th percentile, and outliers.
5. Publish source data, analysis scripts, reproducible tests, and a carefully qualified editorial summary.

Official documentation:
- [Coinbase Exchange historical candles](https://docs.cdp.coinbase.com/exchange/reference/exchangerestapi_getproductcandles)
- [Kraken OHLC](https://docs.kraken.com/api/docs/rest-api/get-ohlc-data)

## Technology

Current published prototype: HTML, CSS, vanilla JavaScript, inline SVG, responsive design and accessible buttons. Research pipeline and historical evidence are future publication steps.

## Local preview

Open `index.html` in a browser or run `python3 -m http.server 8000` and visit http://localhost:8000/.

## Authorship and scope

This is a standalone, independently presented interactive research prototype. Any historical results will be identified separately from synthetic demonstrations. Source code and published claims are intended to remain auditable.

## Contact

[GitHub profile](https://github.com/Claire-uuu)
