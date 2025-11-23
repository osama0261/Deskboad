# 📊 Amazon Sales – Power BI Dashboard

This repository contains a Power BI report for analyzing **Amazon Sales data**.  
The `.pbix` file includes interactive visuals to track revenue, orders, profit, top products, and performance across regions and time.

---

## ✨ Key Features

- 📈 **Sales Overview**
  - Total Sales
  - Total Orders
  - Total Profit / Margin
  - Average Order Value

- 🕒 **Time-based Analysis**
  - Year / Quarter / Month wise trends
  - Compare current period vs previous period

- 🌍 **Geographical Insights**
  - Sales by Country / Region / State
  - Map visual (if enabled in the file)

- 🧺 **Category & Product Performance**
  - Top-selling categories
  - Best and worst performing products
  - Profitability by category

- 👥 **Customer Insights** (if data available)
  - Repeat vs new customers
  - Customer wise sales contribution

- 🔍 **Interactive Filters (Slicers)**
  - Date Range
  - Region / Country
  - Category / Sub-category
  - Order Status, etc.

> Note: Exact visuals depend on the final version of the `.pbix` file, but the above are typical components of an Amazon sales dashboard.

---

## 🗂️ Project Structure

Aap GitHub repo ko is tarah structure kar sakte ho:

```bash
amazon-sales-powerbi/
├── AMAZON SALES.pbix        # Main Power BI report
├── data/                    # (Optional) Raw / cleaned data files
│   ├── amazon_sales.csv
│   └── README_DATA.md
├── screenshots/             # Dashboard screenshots for GitHub
│   ├── overview.png
│   ├── category_view.png
│   └── map_view.png
└── README.md                # Project documentation (ye file)
