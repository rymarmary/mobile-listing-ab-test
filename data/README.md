# Data

The notebook expects two CSV files in this directory:

- `ab_visits.csv` — one row per visit (visitor token, visit id, started at, url, experiment assignment, page views per visit)
- `ab_orders.csv` — one row per order (order id, state, platform fee in RUB, visit id)

Schema details are documented in the analysis notebook.

## Why the files are not in this repo

This analysis was a take-home exercise for a real travel marketplace. The underlying user-level data is proprietary and is not redistributed here. The notebook, methodology, and results in the README cover the full analysis end-to-end.
