# Superstore Sales — Data Cleaning & EDA

Performed data cleaning and exploratory data analysis on the Superstore Sales dataset using Python (pandas, NumPy, matplotlib, seaborn).

## Dataset
[Superstore Sales — Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## What was done
- Checked and confirmed no missing values or duplicates
- Fixed date column data types (Order Date, Ship Date)
- Investigated outliers in Sales and Profit — retained, as they represent real large transactions rather than data errors
- Visualized data using histograms, bar charts, box plots, and a correlation heatmap

## Key Insights
- Sales is heavily right-skewed — most orders are under ₹500, with a long tail of large bulk orders
- Technology generates the highest total sales, followed closely by Furniture and Office Supplies
- Discount is negatively correlated with Profit (-0.22) — heavier discounting erodes margins
- Sales and Profit show a moderate positive correlation (0.48)

## Tools
Python, pandas, NumPy, matplotlib, seaborn, Google Colab
