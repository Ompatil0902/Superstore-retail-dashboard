# 📊 Superstore Sales & Profitability Analysis Dashboard

[![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Power Query](https://img.shields.io/badge/Power_Query-ETL_Pipelines-orange?style=for-the-badge)](https://support.microsoft.com/en-us/excel)
[![Power Pivot](https://img.shields.io/badge/Power_Pivot-DAX_Data_Model-blue?style=for-the-badge)](https://support.microsoft.com/en-us/excel)

An interactive Business Intelligence analytics solution engineered inside Microsoft Excel. This project extracts, normalizes, and transforms raw commercial retail transaction records into an analytical **Star Schema** using **Power Query**, calculates custom multi-dimensional financial metrics with **Power Pivot (DAX)**, and presents an interactive presentation layer with **Pivot Tables**, **Pivot Charts**, and synchronized **Slicers**.

---

## 🎯 Project Objectives

* **Automate Data Transformation**: Ingest and clean messy transactional flat files via Power Query, automating transformations and eliminating manual sheet manipulation.
* **Star Schema Implementation**: Deconstruct denormalized retail logs into dedicated Dimension and Fact tables to eliminate redundancy and build an enterprise-grade data model.
* **Dynamic KPI Modeling**: Formulate explicit DAX measures inside Power Pivot to calculate operational metrics (Total Revenue, Net Profit, and Margin percentages) dynamically across any slice or context.
* **Interactive Executive Reporting**: Create a dynamic dashboard UI enabling business leaders to evaluate categorical profitability and diagnose margin compression.

---

## ❓ Business Questions Answered

1. **Top-Line & Bottom-Line Performance**: What is the company's total realized gross revenue and bottom-line net profit?
2. **Operational Margin Health**: What is the overall profit margin percentage across all operations?
3. **Category Profitability Disparities**: How do profit margins vary across product categories (`Furniture`, `Office Supplies`, `Technology`), and which category represents a financial risk?
4. **Interactive Cohort Slicing**: How do revenue and profit shift when stakeholders filter by specific operational product categories?

---

## 🔄 End-to-End Workflow

```text
[ Raw Transaction Logs: RawOrders, RawReturns, RawPeople ]
                             │
                             ▼
                [ Power Query ETL Pipeline ]
  • Cleaned column headers, removed nulls & trailing spaces
  • Standardized data types (Currency, Dates, Geography, Keys)
  • Merged returns & regional manager mapping tables
  • Separated flattened records into Dimension & Fact entities
  • Generated custom calendar tables (DimDate, DimShipDate)
                             │
                             ▼
                 [ Power Pivot Data Model ]
  • Loaded tables into the internal xVelocity VertiPaq engine
  • Established 1-to-Many (*) relationships (Star Schema)
  • Defined explicit DAX measures in Power Pivot
                             │
                             ▼
               [ Calculation & Presentation Layers ]
  • "Pivot Work": Staging sheet running underlying Pivot aggregations
  • "dashboard": Presentation plane with Pivot Charts, KPI cards, & Slicers
