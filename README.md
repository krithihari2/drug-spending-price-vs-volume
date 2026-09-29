# Medicare Part D Drug Spending: Price vs. Volume

Medicare Part D spent **$94.6 billion more** on prescription drugs in 2024 than in 2020. This project asks where that growth came from. Did drugs get more expensive, or were more prescriptions filled?

**Status:** In progress

## Key findings

- **Spending rose 48.7%**, from $194.1B in 2020 to $288.7B in 2024. That's about 10.4% a year.
- **Price was the bigger driver.** The average price per dosage unit rose 25.6%, while the number of units rose 18.4%. Of the $94.6B increase:

  | Source | Amount | Share of growth |
  |---|---|---|
  | Price | $49.7B | 52.6% |
  | Volume | $35.7B | 37.8% |
  | Both changing together | $9.1B | 9.7% |

- **Growth was concentrated in a few drugs.** 15 of 3,625 drugs account for 70% of the increase ($66.1B). Most treat diabetes or heart disease: Ozempic, Eliquis, Jardiance, Mounjaro and others.
- **GLP-1 drugs alone contributed 21.7%** ($20.5B). Ozempic, Mounjaro, Trulicity and Rybelsus make up most of it.
- **Some growth that looks new is patients switching to a generic.** For example, generic lenalidomide added $2.6B, but about $1.2B of that replaced spending on the brand-name drug, Revlimid. Combined, the drug grew through more patients (+32% units), not higher prices.

## Data

[Medicare Part D Spending by Drug](https://data.cms.gov/summary-statistics-on-use-and-payments/medicare-medicaid-spending-by-drug/medicare-part-d-spending-by-drug), published by the Centers for Medicare & Medicaid Services (CMS). The 2026 release covers 2020–2024. It reports total spending, dosage units, claims and beneficiaries for each drug.

## Tools

Python, DuckDB (SQL), pandas, matplotlib

## Author

Krithi Hari
