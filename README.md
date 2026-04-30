How the Cost of Living Changed in Nigeria (2023–2026)

**Author:** Towoju Blessing Eniola

**Course:** Kujenga Final Project

**Country:** Nigeria

**Date:** April 2026

## The Question

How significantly did the cost of living change in Nigeria between 2023 and 2026, and what does that mean for ordinary households?

## What This Project Does

This project uses real monthly data from the National Bureau of Statistics and the Central Bank of Nigeria to track how inflation and the naira's exchange rate moved between March 2023 and March 2026. It then builds a Multiple Linear Regression model to measure what was actually driving inflation, and translates all of that into a simple naira answer: what did it actually cost to survive?

The story is told through three characters — Amaka (a market woman in Lagos), Jide (a civil servant in Ibadan), and Usman (a business owner in Kano) — whose experiences reflect what the data shows about how different Nigerians absorbed the crisis.

## Key Findings

- Headline inflation peaked at 34.80% in December 2024, up from 22.04% in March 2023
- The naira fell from ₦461.50 per dollar to a peak of ₦1,670 per dollar by November 2024
- A household spending ₦50,000 per month in March 2023 would have needed ₦107,738 per month by March 2026 to afford the same things
- Exchange rate and MPR together explain 45.6% of inflation variation over the period

## Files in This Repository

| File | Description |
|------|-------------|
| `TowojuBlessing_Nigeria_final_project.ipynb` | Main project notebook |
| `project_dataset.xlsx` | Dataset covering March 2023 to March 2026 |
| `surviving_not_living_v3.html` | Cartoon story introducing the three characters |

## Data Sources

| Dataset | Source |
|---------|--------|
| Monthly Headline, Food and Core Inflation | National Bureau of Statistics (NBS) Monthly CPI Reports |
| Monetary Policy Rate (MPR) | Central Bank of Nigeria (CBN) MPC Official Decisions |
| NGN/USD Exchange Rate | CBN / TheGlobalEconomy.com |

## How to Run

1. Open [Google Colab](https://colab.research.google.com)
2. Go to File > Open notebook > GitHub tab
3. Paste this repository link and select the notebook
4. Run all cells from top to bottom

The notebook loads the dataset directly from this GitHub repository so no local setup is needed.

## Tools Used

- Python 3
- pandas
- matplotlib
- scikit-learn
