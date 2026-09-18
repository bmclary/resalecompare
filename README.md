# Resale Compare

An independent tool for comparing Disney Vacation Club (DVC) resale contracts apples-to-apples on true lifetime cost per point, and generating a recommended offer based on tracked comparable contracts.

Live at [resalecompare.com](https://resalecompare.com).

## What it does

Enter multiple DVC resale contracts from broker sites (list price, closing costs, transfer fee, points remaining) and see side-by-side:

- **Total Projected Dues** through contract expiration, using each resort's actual historical CAGR
- **2026 & 2027 Dues Credits** (with checkbox controls for whether they're already baked into list price)
- **Total Lifetime Cost** and **Lifetime $/Point** — the true apples-to-apples number

Star your target contract, and the tool reverse-engineers a **recommended offer** based on the best qualifying same-resort comp in the same contract-size tier (Small: <100 pts, Standard: 100–300, Jumbo: >300).

## Features

- Comparison table with sortable columns and frozen row identifier
- Sticky Home Resort + Use Year columns while scrolling horizontally
- Recommended offer with cash-to-close breakdown
- Shareable URLs — all contracts encoded in the URL for bookmarking or sharing
- CSV export of contracts and calculated values
- Works entirely client-side — no backend, no user data collected

## Tech

Single self-contained `index.html` file. Vanilla JavaScript, CSS variables, no build step. Hosted on Vercel.

## Feedback

Email [hello@resalecompare.com](mailto:hello@resalecompare.com) — feedback shapes what gets built next.

## Disclaimer

Not affiliated with Disney or Disney Vacation Club. For educational purposes only; verify all details with your resale broker before buying.
