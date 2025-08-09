# 5G Tower Clustering

This project groups 5G tower sites in Uttarakhand using Python and KMeans clustering. It helps identify areas where more towers are needed or where there are too many, using simple data analysis and visualizations.

---

## What It Does

- Cleans and prepares tower site data (`Lat`, `Long`, `Tower Type`)
- Groups towers into clusters using KMeans
- Shows clusters and tower types in simple plots
- Gives basic suggestions: where to expand or reduce sites

---

## Files

- `Site_5g.ipynb` — Main notebook with all code and analysis
- `sample_data.number` — Small sample Excel for trying out the code
- `requirements.txt` — Libraries needed
- `README.md` — This file

---

## How to Use

1. Open the notebook in Colab, Jupyter, or VS Code with Jupyter support
2. Use the sample data or your own file (must have `Lat`, `Long`, `Tower Type`)
3. Run all cells to see clustering and recommendations

---

## Note

The original, full dataset is not included. Use `sample_data.xlsx` as a demo, or add your own data in the same column format.

---

## Tech

- Python, pandas, scikit-learn, matplotlib, seaborn, openpyxl

