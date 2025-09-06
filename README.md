# Sales Analysis & Visualization (2019 Data)

This project demonstrates Sales Data Analysis using Python (Jupyter Notebook) for data preparation and Power BI for interactive dashboards.
The dataset contains 12 months of sales transactions (2019), which were cleaned, transformed, and visualized to generate insights.

## Project Setup
# 1. Clone Repository
git clone https://github.com/yourusername/sales-analysis.git
cd sales-analysis

# 2. Dataset

The dataset is a combined CSV file: twelve_months_data.csv

Columns include:

Order ID

Product

Quantity Ordered

Price Each

Order Date

Purchase Address

# Requirements
Python (Jupyter Notebook)

Install dependencies:

Download Power BI Desktop

Official Microsoft page:
👉[ Download Power BI Desktop](https://www.microsoft.com/en-us/download)

Alternative (from Microsoft Store, Windows 10/11):
👉 [Power BI Desktop (Microsoft Store)](https://apps.microsoft.com/detail/9ntxr16hnw1t?hl=en-gb&gl=US)

🔹 Download Jupyter Notebook

Jupyter comes with Anaconda (recommended) or can be installed via pip.

Anaconda Distribution (recommended, includes Jupyter + Python + packages)
👉 [Download Anaconda](https://www.anaconda.com/download)

Install via pip (if Python already installed)
 in cmd:
 -pip install notebook
Run Jupyter Notebook with:
 -jupyter notebook
Import the cleaned dataset twelve_months_data.csv

Load the Power BI dashboard file (.pbix) included in the repo.

## ▶How to Run the Project
Step 1: Data Cleaning in Jupyter Notebook

Open Sales_Analysis.ipynb

Run all cells to:

Merge 12 months’ data

Clean anomalies (NaN, Nulls, Duplicates)

Add calculated columns (Sales, Month, Hour, City)

Export the final dataset twelve_months_data.csv

Step 2: Visualization in Power BI

Open Sales_Analysis.pbix in Power BI Desktop

Measures Created:

Total Orders

Total Quantity

Total Sales

Profit

Average Order Value (AOV)

Visuals Added:

Area Chart: Sales by Hour

Bar Chart: Month vs Sales

Bar Chart: City vs Sales

Tree Map: Product vs Quantity Ordered

Map: City-wise Sales (bubble map)

KPI Cards: Sales, Profit, Orders, AOV

Slicers: Product, City, Month

📈 Key Insights

Peak sales observed during holiday months (Nov–Dec)

Evening hours (7–9 PM) had highest order volumes

San Francisco led in total sales across cities

Top products: Batteries, USB-C cables, and electronics

Profit margin analysis highlighted high-performing products

🙌 Thank You

📧 Email: yourname@example.com

🐙 GitHub: yourusername
