# 🛒 Walmart Sales Analysis Dashboard

This project explores and visualizes Walmart’s historical weekly sales data across 45 stores and multiple departments in the USA using Python and Tableau Public. It aims to identify sales trends, regional/store performance, holiday impacts, and top-performing departments.

---

## 🔍 Business Questions

- 📆 What months or seasons generate the most sales?
- 🏪 Which store types perform best?
- 📦 What are the top-performing departments?
- 🎉 Do holiday weeks drive more revenue?
- 📊 Can we present these findings through an interactive dashboard?

---

## 📁 Dataset

- Source: [Kaggle – Walmart Store Sales Forecasting](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting/data)
- Files used:
  - `train.csv`, `features.csv`, `stores.csv`

---

## 🧼 Data Cleaning (Excel)

Performed in Excel before analysis:
- Joined all datasets using `Store` and `Date` keys
- Created new fields: `StoreDateKey`, `Type`, `Size`, `IsHoliday_feat`
- Checked holiday column consistency
- Created pivot tables for initial exploration

---

## 🐍 Python Analysis (Jupyter Notebook)

Performed group-based analysis and visualizations using:

- `pandas`, `matplotlib`
- Monthly sales trend
- Holiday vs. non-holiday revenue
- Store type comparison
- Top 10 departments by revenue

**Notebook location**: `notebooks/walmart_sales_analysis.ipynb`

---

## 📊 Tableau Dashboard (Interactive)

Built a professional dashboard showing:

- Monthly revenue trends 📈
- Top departments 📦
- Store type performance 🏪
- Holiday vs. non-holiday impact 🎉

**🔗 View Live Dashboard**:  
[https://public.tableau.com/views/walmart_dashboard/Dashboard1](https://public.tableau.com/views/walmart_dashboard/Dashboard1)

---

## 📈 Key Findings

- 🏆 July had the highest sales across all stores
- 📉 January had the weakest performance
- 🎯 Store Type A generated the highest total revenue
- 🧪 Holiday weeks averaged **7% more sales** than regular weeks
- 🧱 Top 10 departments drove the majority of revenue

---

## 📢 Business Recommendations

- 📆 Focus campaigns around July, April, and December
- 🛍️ Prioritize inventory for top departments
- 🎯 Retarget customers during post-holiday periods
- 🎉 Leverage holiday-specific marketing

---
## 📂 Repository Structure
```
walmart-sales-dashboard/
│
├── data/
│ ├── raw/ # Original Kaggle files
│ └── processed/ # Cleaned Excel workbook
│
├── excel_cleaning/ # Excel sheets and pivots
│
├── notebooks/
│ └── walmart_sales_analysis.ipynb
│
├── visuals/ # Python-generated charts
│
├── dashboard/
│ └── walmart_dashboard.twbx
│
└── README.md
```
---
## 🌐 Author

**Oyenekan Larry**  
📧 [LinkedIn](https://www.linkedin.com/in/oyenekan-olanrewaju-745651293)  
📂 [GitHub](https://github.com/Larry0615)
