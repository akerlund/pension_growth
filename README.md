# Pension Growth Calculator

This repository contains a single-file pension calculator you can open directly in a web browser.

GitHub does not render repository HTML files as normal web pages when you click them from a README on github.com. It shows the file view instead.

To get a browser-rendered version from GitHub, use GitHub Pages:

- Live site: https://akerlund.github.io/pension_growth/
- Direct calculator page: https://akerlund.github.io/pension_growth/pension_growth_calculator.html

The calculator helps estimate:
- pension growth before retirement
- monthly pension payout after retirement
- yearly balances during accumulation and drawdown
- the effect of fees, inflation, taxes, and changing contribution levels

## File

- `pension_growth_calculator.html`

## Features

- Start amount and expected annual growth
- Monthly private investment
- Monthly employer/state contribution
- Separate yearly increase rates for private and employer/state contributions
- Years until retirement and years in retirement
- Annual inflation
- Annual fee drag
- Withdrawal tax
- Retirement payout mode:
  - inflation-adjusted
  - nominal
- Retirement year comparison table
- Accumulation and drawdown charts
- Year-by-year tables

## Usage

If GitHub Pages is enabled for this repository, click:

- [Open the live calculator](https://akerlund.github.io/pension_growth/)
- [Open the calculator page directly](https://akerlund.github.io/pension_growth/pension_growth_calculator.html)

Open the calculator directly in your browser:

```bash
xdg-open pension_growth_calculator.html
```

You can also open it from VS Code with the built-in browser or Simple Browser.

## GitHub Pages

To make the README links open the rendered calculator from GitHub:

1. Push this repository to GitHub.
2. Open the repository settings.
3. Go to `Pages`.
4. Set the source to deploy from the main branch root.
5. Save and wait for GitHub Pages to publish.

After that, the live URL should be:

`https://akerlund.github.io/pension_growth/`

## Saving values

The page saves entered values in the browser using:
- a cookie
- `localStorage` as a fallback

This means your entered values are normally not stored in the HTML file itself.
If you upload this repository to GitHub, the browser-saved values are not included.
Only the default values written in the HTML source are included.

## Notes

- The calculator is client-side only.
- No build step or dependencies are required.
- It is intended as a planning tool, not financial advice.