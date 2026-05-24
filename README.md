# Techie Academy: Pizza Sales Performance Dashboard

An interactive Power BI Desktop dashboard designed to analyze and visualize sales performance metrics for a pizza restaurant chain. This project transforms raw operational data into actionable business intelligence, highlighting key revenue drivers, sales distributions, and product performance.

## 📊 Project Overview

This dashboard provides a comprehensive look into daily operations and sales trends. By analyzing datasets across orders, pizza categories, and sizes, it allows stakeholders to quickly identify top-performing products and optimization opportunities.

### Key Insights Tracked:
* *Financial Metrics:* Total Revenue, average order value, and gross sales performance.
* *Product Breakdown:* Sales distribution dynamically calculated across different pizza categories (e.g., Classic, Supreme, Veggie, Chicken) and sizes (S, M, L, XL).
* *Operational Trends:* Order volume tracking to identify peak sales periods.

---

## 🛠️ Tech Stack & Architecture

* *Analytics Tool:* Power BI Desktop (Version 1.28 format framework)
* *Data Modeling:* Star Schema design featuring explicit relationships between sales facts and dimension tables (orders, order_details, pizzas, pizza_types).
* *Calculations:* Advanced DAX (Data Analysis Expressions) used for key metrics such as Total_Revenue and Pizza_sold_By_Category_Size.

---

## 📁 Repository Structure

The project files represent the extracted development state of the Power BI workbook layout:

```text
├── Techie_Academy.zip/           # Extracted Power BI project files
│   ├── DataModel                 # Compressed data schema and business logic
│   ├── Report/
│   │   ├── Layout                # Visual container definitions and canvas configuration
│   │   └── StaticResources/      # Custom themes and visual specifications (CY25SU11 Theme)
│   ├── DiagramLayout             # Relationship mapping layout for the model view
│   └── [Content_Types].xml       # Core file package content definitions
└── README.md                     # Project documentation
