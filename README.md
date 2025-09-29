# US Leading Economic Indicators Dashboard

Comprehensive dashboard tracking 7 key US economic leading indicators with automated weekly updates.

## Indicators Included

1. **Payrolls Diffusion Index** - 3-month moving average across 21 employment sectors
2. **EPOP from 24-month high** - Employment-Population Ratio deviation
3. **Continuing Claims (inverted)** - % above 3-year lows
4. **New Orders** - Manufacturing new orders from 24-month highs
5. **Building Permits** - As % of 24-month high
6. **Manufacturing Orders to Inventories** - From 24-month high
7. **PCE Spending Diffusion** - Year-over-year growth across spending categories

## Data Sources

- FRED (Federal Reserve Economic Data) via pandas-datareader
- BEA (Bureau of Economic Analysis) for PCE data

## Updates

Dashboard updates automatically every Monday at 12:00 UTC via GitHub Actions.

## View Dashboard

[View Live Dashboard](https://datavizhonduran.github.io/us-leading-indicators/)

---

Last update timestamp is shown at the bottom of the dashboard.
