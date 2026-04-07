# Tradeshow Dashboard — SCO Scan Integrity

Interactive demo dashboard for tradeshow and client presentations. Visualizes how Vision AI detects scan-miss incidents at self-checkout (SCO) lanes and quantifies recovered revenue.

## Live demo

[View dashboard →](https://ypoons0602-dotcom.github.io/tradeshow-dashboard)

## What this shows

A single-page interactive report built around a Sankey-style transaction flow, designed to help retail clients self-read the data without explanation:

- **Transaction integrity flow** — traces every SCO transaction from total volume through AI detection, staff/customer rescan response, and final financial outcome
- **AI insights** — two natural-language cards summarizing what AI recovered this period and the remaining opportunity
- **Key metrics** — scan-miss rate, rescan rate, revenue recovered, and revenue at risk

## Filters

| Filter | Options |
|--------|---------|
| Time period | Q1 / Q2 / Q3 2025, Q4 2024 |
| Store | Store Alpha, Beta, Gamma (anonymized) |

All numbers update dynamically on filter change — no page reload required.

## Data

All figures are **illustrative mock data** for demo purposes only. No real transaction or store data is included.

## Stack

Single-file HTML — no build step, no dependencies to install.

- React 18 (CDN via unpkg)
- Babel Standalone (JSX transpilation in-browser)
- SVG for the Sankey flow visualization
- Pure CSS for layout and theming

## Deployment

Hosted via GitHub Pages from the `main` branch. Any push to `main` triggers an automatic redeploy.

To run locally, simply open `index.html` in a browser — no server required.
