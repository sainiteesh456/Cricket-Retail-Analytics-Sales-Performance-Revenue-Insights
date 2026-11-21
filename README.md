# Cricket_Equipent_analysis-Power_BI-Python-Excel-
# 🏏 Cricket Equipment Sales & Regional Revenue Analysis (India)

An end-to-end data analytics project comparing revenue generated across all cricket equipment categories across major cities in India using **Excel**, **Python**, and **Power BI**.

---

## 📌 Project Overview
This project analyzes retail transaction data for cricket gear across Indian markets to uncover regional revenue drivers, evaluate top-performing equipment categories, and compare performance between online and offline sales channels. 

### 🎯 Key Objectives
* **Regional Revenue Comparison:** Evaluate and rank revenue generated across different Indian cities to identify high-performing markets.
* **Category Performance:** Compare overall revenue contributions across all cricket equipment categories (e.g., bats, balls, protective gear, apparel).
* **Data Cleaning & Standardization:** Handle missing values, standardize city names and categories, and validate data types.
* **Feature Engineering:** Calculate net revenue post-discount in INR and analyze discount impacts on order volume.
* **Interactive Reporting:** Build a dynamic Power BI dashboard to track KPIs and slice performance by city, sales channel, and product category.

---

## 🛠️ Tech Stack & Workflow

1. **Microsoft Excel**
   * Initial raw data inspection (`raw_cricket_equipment_sales.csv`), formatting checks, and preliminary city-wise pivot table summaries.
2. **Python (Pandas, NumPy, Matplotlib, Seaborn)**
   * **Data Preprocessing:** Stripped whitespace and standardized casing for categorical fields (`city`, `equipment_category`, `sales_channel`) in `cric_equipment_analysis.ipynb`.
   **Exploratory Data Analysis (EDA):** Generated histograms and grouped bar plots to inspect revenue distribution across Indian cities, sales channels, and equipment categories.
3. **Power BI**
   * **Data Modeling & DAX:** Connected `cric.csv` to `cric.pbix` and created custom measures for Total Revenue (INR), Average Order Value (AOV), Total Units Sold, and Average Customer Rating.
   * **Interactive Dashboard:** Designed visual reports featuring city-level revenue comparisons, equipment category breakdowns, and dynamic slicers.

---

## 🧮 Revenue Calculation & Methodology
To accurately compare performance across cities and equipment types, net revenue was calculated using the following logic:
* **Net Revenue Formula:** `Quantity × Unit Price (INR) × (1 - Discount % / 100)`
* **Aggregation:** Grouped transaction-level records by **City** and **Equipment Category** to evaluate total revenue contribution, average order value (AOV), and units sold.

---

## 📂 Repository Structure
```text
Cricket_Equipment_analysis/
│
├── raw_cricket_equipment_sales.csv   # Original raw dataset
├── cric.csv                          # Cleaned and processed dataset exported from Python
├── cric_equipment_analysis.ipynb     # Python notebook for data cleaning, feature engineering & EDA
├── cric.pbix                         # Interactive Power BI dashboard file
├── dashboard_preview.png             # Screenshot of the Power BI dashboard (optional)
└── README.md                         # Project documentation
```
---

---

## 📬 Contact
Created by **Niteesh Samavedam** – feel free to connect on [LinkedIn](https://www.linkedin.com/in/sai-niteesh-a97128261) or reach out via email for feedback and collaboration!
