# County Rainfall and Planting Advisory

## Project Summary

This project analyses monthly rainfall data for Nairobi, Nakuru, Kisumu, Mombasa and Machakos. The Machakos data contained invalid values, which were cleaned and replaced using the rounded average of the valid Machakos readings. NumPy was then used to calculate annual rainfall totals, monthly averages, wettest months, dry months and recommended planting windows.

## How to Run

Open `rainfall_analysis.ipynb` in Google Colab and run all cells from top to bottom.

## Planting Advisory

- Kisumu recorded the highest annual rainfall at **1,371 mm**, while Machakos recorded the lowest at **811 mm**.
- Nairobi, Nakuru, Kisumu and Mombasa have their strongest two-month rainfall period in **April-May**, while Machakos has its strongest period in **November-December**.
- Machakos has **6 dry months** compared with **0 dry months in Kisumu**, so the NGO should provide county-specific planting advice rather than using one recommendation for all counties.
