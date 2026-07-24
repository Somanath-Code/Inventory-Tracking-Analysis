# Inventory Tracking Analysis

Exploratory data analysis of a sample inventory dataset (500 records, 7 products,
5 warehouses, 4 suppliers) using Python, Pandas, Matplotlib, and Seaborn.

## What this covers
- Data cleaning & quality checks (missing values, duplicates)
- Stock level analysis by product and warehouse
- Reorder point analysis — flagging understocked vs. overstocked items
- Warehouse performance comparison
- Supplier shortage and lead-time analysis
- Correlation testing: does lead time or unit cost predict shortfalls?

## Key finding
Overstocking, not stockouts, is the dominant issue — 373 of 500 products are
overstocked vs. 66 running low. Neither supplier lead time (r = -0.10) nor
unit cost (r = 0.06) meaningfully explains the shortfalls, pointing toward
reorder-point calibration as the likely fix.

## How to run
1. Clone this repo
2. Add `Inventory-Tracking.xlsx` to the project folder (sample dataset)
3. Open `Inventry_Tracking.ipynb` in Jupyter
4. Run all cells

## Tools
Python · Pandas · Matplotlib · Seaborn

## Note
This project uses a sample/practice dataset (not real company data). AI tools
were used for debugging and preparing presentation guidance — see the Development Notes
section in the notebook for details.

---
Somanath Tripathy | Aspiring Data Analyst
