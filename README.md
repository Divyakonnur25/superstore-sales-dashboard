# superstore-sales-dashboard
Sales performance dashboard built with Python, Excel &amp; Power BI.
# 🛒 Superstore Sales Performance Dashboard

![Dashboard Preview](Screenshot%20(219).png)

[![Python](https://img.shields.io/badge/Python-Pandas-blue?style=flat&logo=python)](https://www.python.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=flat&logo=powerbi)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Excel-Data%20Analysis-green?style=flat&logo=microsoftexcel)](https://www.microsoft.com/excel)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)]()

---

## 📌 Project Overview

Analyzed **9,800 sales transactions** from a US Superstore dataset to uncover revenue trends, top-performing customer segments, regional patterns, and shipping insights.

This project was built as part of my **Data Science Internship at KodNest**, applying end-to-end data analysis skills — from raw data cleaning to an interactive business dashboard.

---

## 🎯 Business Questions Answered

- Which **customer segment** drives the most revenue?
- Which **product categories and sub-categories** perform best?
- Which **months** have the highest and lowest sales?
- How does **shipping mode** affect order volume?
- Which **regions** contribute the most to total sales?

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Python (Pandas)** | Data cleaning, EDA, feature engineering |
| **Excel** | Data validation & pivot table exploration |
| **Power BI** | Interactive dashboard & data visualization |
| **Jupyter Notebook** | Analysis environment |

---

## 📊 Dashboard Preview

> Built with Power BI — includes KPI cards, bar charts, treemap, line chart, and interactive slicers for year and region.

![Dashboard](Screenshot%20(219).png)

---

## 🔍 Key Findings

| Insight | Finding |
|---------|---------|
| 🏆 Top Segment | **Consumer** leads with 129K in sales — 50%+ of total revenue |
| 📅 Best Month | **February** highest sales month at **43K** |
| 🚚 Shipping | **Standard Class** dominates with **135K** orders |
| 💻 Top Category | **Technology** is the highest revenue-generating category |
| 📍 Top Sub-Category | **Chairs & Phones** are the top-selling sub-categories |
| 🌍 Regional Sales | **West** region leads in total sales contribution |

---

## 🧹 Data Cleaning Steps (Python · Pandas)

- Removed null values and duplicate rows
- Standardized date formats (`order_date`, `ship_date`)
- Created new columns: `order_month`, `order_year`, `order_day`
- Validated data types for numeric and categorical columns
- Exported clean dataset for Power BI consumption

---

## 📈 Dashboard Features (Power BI)

- **4 KPI Cards** — Total Sales, Order Count, Customer Count, Avg Sales
- **Sales by Segment** — Area/line chart comparing Consumer, Corporate, Home Office
- **Top Sub-Categories** — Bar chart of best performing products
- **Sales by Month** — Horizontal bar chart showing monthly trends
- **Sales by Category** — Treemap showing Technology, Office Supplies, Furniture
- **Sales by Region** — Line chart across weekdays per region
- **Sales by Ship Mode** — Bar chart comparing shipping methods
- **Interactive Slicers** — Filter by Year (2015–2018) and Region

---

## 🚀 How to Run

1. **Clone this repo:**
```bash
git clone https://github.com/Divyakonnur25/superstore-sales-dashboard.git
```

2. **Open the Jupyter Notebook:**
```bash
cd superstore-sales-dashboard
jupyter notebook superstore.ipynb
```

3. **Open the Power BI Dashboard:**
   - Open `superstore1.pbip` in **Power BI Desktop**

---

## 💡 What I Learned

- Real-world **data cleaning** with Pandas — handling nulls, duplicates, type errors
- **Business thinking** — translating data into actionable insights
- **Power BI** dashboard design — KPI cards, slicers, chart formatting
- **Storytelling with data** — presenting findings clearly for a business audience

---

## 👤 Author

**Divya Konnur**


*⭐ If you found this project helpful, please give it a star!*
