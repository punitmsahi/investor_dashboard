# Investor Tearsheet — Systematic Trend-Following (NSE F&O)

A single self-contained static page (`index.html`) presenting the live backtest performance of a
daily-adaptive, risk-managed futures program trading NSE-listed stocks and indices — cumulative
return, risk stats, drawdown, trade signature, sector/direction breakdown, out-of-sample
validation, and a NIFTY 50 benchmark comparison, with a global trailing-period selector (3M/6M/1Y/
2Y/5Y/full history).

This repo intentionally contains **only the presentation layer** — every number here is derived
from a backtest run against a proprietary strategy whose code, parameters, and data live in a
separate, private codebase. No indicator periods, thresholds, or entry/exit logic are disclosed on
this page or in this repo.

## Updating

The page is regenerated from a fresh backtest report and republished as a whole; there's no build
step. To update the live site, replace `index.html` with the newer version and redeploy (or push to
the branch Netlify is watching, if continuous deployment is configured).

## Local preview

Just open `index.html` in a browser — no server or build tooling required.
