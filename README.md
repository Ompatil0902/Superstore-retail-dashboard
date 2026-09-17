# 📊 Superstore Sales & Profitability Analysis Dashboard

[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Power Query](https://img.shields.io/badge/Power_Query-Data_Transformation-orange?style=for-the-badge)](https://support.microsoft.com/en-us/excel)
[![Power Pivot](https://img.shields.io/badge/Power_Pivot-DAX_Modeling-blue?style=for-the-badge)](https://support.microsoft.com/en-us/excel)

An end-to-end interactive Business Intelligence dashboard built inside Microsoft Excel utilizing **Power Query**, **Power Pivot (Data Modeling & DAX)**, **Pivot Tables**, **Pivot Charts**, and interactive **Slicers**. This project analyzes commercial retail transactions to evaluate high-level revenue performance, profitability, and categorical health.

---

## 🎯 Project Objectives

- **Centralize Data Architecture**: Extract, clean, and model normalized transaction data using Power Query and Power Pivot.
- **Track Core Financial KPIs**: Measure operational metrics including Total Sales, Gross Profit, and Overall Profit Margin.
- **Categorical Performance Evaluation**: Uncover margins across product lines (Furniture, Office Supplies, Technology) to identify profitability bottlenecks.
- **Interactive Self-Service Reporting**: Empower business stakeholders to dynamically filter and drill down across categories without altering underlying data tables.

---

## ❓ Key Business Questions Answered

1. **Overall Performance**: What is the company's total gross sales volume and net realized profit?
2. **Margin Health**: What is the overall profit margin percentage across all operations?
3. **Category Disparities**: Which product category yields the highest margin, and which category is underperforming despite sales volume?
4. **Interactive Filtering**: How do key financial figures shift when isolating specific operational categories?

---

## 🔄 End-to-End Workflow

```text
[ Raw Transactional Data / CSVs ]
                 │
                 ▼
     [ Power Query ETL Engine ]
       - Removed duplicates & nulls
       - Standardized data types (Currency, Dates, Text)
       - Split entities into Fact & Dimension schemas
                 │
                 ▼
      [ Power Pivot Data Model ]
       - Built 1-to-Many Star Schema relationships
       - Established active primary & foreign keys
                 │
                 ▼
       [ DAX Measure Engine ]
       - Computed dynamic metrics (Sales, Profit, Margin %)
                 │
                 ▼
   [ Excel Analytics & UI Presentation ]
       - Pivot Tables & Pivot Work calculation tab
       - Dynamic Pivot Charts
       - Interactive Slicers & clean UI layout
