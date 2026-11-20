# Stock DCF Models

An interactive discounted-cash-flow (DCF) valuation calculator covering **31 companies across nine industries**, built from SEC filing data. Each company tab reprices intrinsic value per share against the current market price, with editable assumptions, sensitivity grids, and a "through the legends' eyes" panel (Buffett, Graham, Lynch, Munger, Marks) that applies each investor's discipline to the same numbers.

**To use it:** open `index.html` in any browser. No build step, no dependencies — it is a single self-contained file.

## Attribution

**This project was built entirely by Muse, Meta's personal AI agent (Muse Spark).** All of the code, the filing research, the data compilation, and the methodology refinements are the work of Muse by Meta. It was created for Sabin Bhattarai, who commissioned it, set the requirements, reviewed the outputs, and made the final assumption calls. It is published here at his direction, with the authorship stated plainly.

## What's inside

- **31 company models** — Technology, Communication Services, Consumer, Energy, Financials, Healthcare, Industrials, Utilities, and Materials — with filing-based free-cash-flow inputs, net-cash/debt bridges, and share counts.
- **A Models tab with an 11-model library:** two-stage DCF, growth-fade (three-stage) DCF, reverse DCF, Buffett owner earnings, Greenwald Earnings Power Value, CAPM/WACC builder, bank residual income & P/B–ROE, dividend discount model, exit-multiple / sum-of-the-parts, a terminal-value consistency check (Damodaran), and a base-rate sanity check.
- **Stock-based-compensation (SBC) adjusted cash-flow bases** — the default on the companies where SBC materially distorts reported free cash flow.
- **Refined every night.** The methodology is improved on a nightly cycle — one verified improvement per night — and **a refinement log** records each change and why it was made.

## Data and snapshot note

Company inputs are drawn from SEC filings (10-K / 10-Q). This repository is a **snapshot as of November 19, 2026** (share prices as of the November 16–19, 2026 closes). The live version is maintained separately and its methodology is refined every night, so figures here will drift from current market data over time.

## Disclaimer

For education and research only. Nothing in this project is investment advice, and DCF outputs are only as good as the assumptions entered into them.
