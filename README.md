# Fictional Retail Dashboard

## Project Overview
This project is a **Sales Insights Dashboard** built using a fictional retail dataset with 10,000 entries. The goal is to clean, analyze, and visualize retail sales data to derive actionable business insights.

---

## Dataset
- Source: `sales_data_clean.csv` (fictional retail dataset)
- Number of records: 10,000
- Columns:
  - `id` – Unique row identifier
  - `InvoiceNo` – Invoice number
  - `StockCode` – Product code
  - `Description` – Product description
  - `Quantity` – Number of items sold
  - `InvoiceDate` – Date of invoice
  - `UnitPrice` – Price per unit
  - `CustomerID` – Customer identifier
  - `Country` – Country of purchase
  - `TotalRevenue` – Calculated as `Quantity * UnitPrice`

---

## Tools Used
- **SQLite Studio** – For data cleaning and transformations
- **Power BI** – For data visualization and dashboard creation
- **Git & GitHub** – For version control and project hosting

---

## Steps Taken
1. **Data Cleaning**
   - Checked for null values and duplicates
   - Corrected invoice dates and added a `TotalRevenue` column
   - Ensured all column names were clean and consistent

2. **Data Analysis & Visualization**
   - Created key performance indicators (KPIs) for total revenue, sales per month, and top-selling products
   - Designed a **Power BI dashboard** with line charts, bar charts, and slicers for interactive filtering
   - Used month/year breakdowns for trend analysis

3. **Project Upload**
   - All files uploaded to GitHub:
     - Cleaned CSV (`data/sales_data_clean.csv`)
     - Power BI file (`pbix/`)
     - Screenshots of the dashboard (`Screenshots/`)
     - This README.md file

---

## Insights
- Revenue trends show clear seasonal patterns.  
- Top products contribute disproportionately to total sales.  
- Customer distribution varies by country, highlighting regional demand differences.

---

## How to Use
1. Clone the repository:
   ```bash
    https://github.com/UtkarshTyagi/fictional_retail_dashboard.git

  2.  Open the Power BI file in the pbix/ folder to view and interact with the dashboard.

  3.  Explore the dataset in data/sales_data_clean.csv for further analysis.





---

## **Screenshots**
See the `Screenshots/` folder for KPIs, charts, and interactive visuals.

---

## **Author**
**Utkarsh Tyagi**
