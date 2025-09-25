# Global-Superstore-Dashboard
## 📌 Objective

Design and publish an **interactive dashboard** using the Global
Superstore dataset to help business stakeholders make data-driven
decisions.

------------------------------------------------------------------------

## 🔑 Key KPIs

-   **Total Sales** → Sum of sales revenue\
-   **Total Profit** → Sum of profits\
-   **Profit Margin %** → Profit ÷ Sales\
-   **Order Count** → Total number of orders\
-   **YoY Growth %** → Year-over-Year growth in Sales\


------------------------------------------------------------------------

## 📊 Dashboard Views

### 1️⃣ Executive Overview

-   KPI cards for Sales, Profit, Margin %, Orders, YoY Growth\
-   Line chart: Monthly Sales Trend\
-   Combo chart: Sales vs Profit\
-   Donut chart: Sales by Category\
-   Insights text box for commentary

### 2️⃣ Regional Deep Dive

-   Map: Sales & Profit by State\
-   Bar chart: Sales by Region\
-   TreeMap: Category / Sub-Category Performance\
-   Table: Top 10 Customers\
-   Slicers: Region, State, Category, Manager

------------------------------------------------------------------------

## ⚡ Interactivity Features

-   Slicers for Date, Region, Category, Segment, Manager\
-   Drilldown hierarchy: Year → Quarter → Month\
-   Drillthrough pages for Region/Customer insights\
-   Bookmarks & buttons for navigation\
-   Cross-filtering & highlighting between visuals

------------------------------------------------------------------------

## 💡 Business Insights

-   Sales grew **\~12% YoY**, led by Technology.\
-   **West region** has highest Sales, while **Central region** has
    lowest Profit Margin.\
-   Top 10 customers contribute nearly **20% of total sales**.\
-   **Furniture sub-category** has high Sales but poor profitability →
    needs cost optimization.

------------------------------------------------------------------------

## 🛠 Technical Notes

-   Dataset: Global Superstore (Orders, Returns, People tables).\
-   Data Model: Orders (fact) linked with Calendar, Returns, People
    (dimensions).\
-   Tool: Power BI Desktop.\
-   Performance Optimization: Aggregations, Top N filtering, Incremental
    Refresh for large datasets.

------------------------------------------------------------------------

## 📂 Repository Structure

    .
    ├── Global_Superstore2.csv          # Dataset
    ├── Global_Superstore.pbix          # Power BI file
    ├── Global_Superstore_Report.pdf    # PDF Report
    ├── README.md                       # Documentation
    └── screenshots/                    # Dashboard Screenshots

------------------------------------------------------------------------

✍️ **Author:** Data Analyst Intern Nitin Kumar

