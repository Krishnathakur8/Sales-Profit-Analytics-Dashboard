# Sales & Profit Analytics Dashboard

An interactive, end-to-end business intelligence dashboard built using Power BI to analyze revenue, profit margins, and order trends across various regions and product categories.

## 🚀 Project Overview
This dashboard was developed to provide stakeholders with a centralized, dynamic view of key business performance indicators. It helps decision-makers track sales growth, evaluate regional performance, and identify top-performing products instantly.

## 🏗️ Data Modeling & Architecture
* **Star Schema Design:** Implemented a clean star schema model featuring a central Fact Table (containing transactional data like sales, profit, and quantity) connected to Dimension Tables (Region, Category, Date).
* **Relationships:** Established robust one-to-many relationships to ensure high query performance and seamless data filtering.
* **DAX Calculations:** Written optimized custom DAX measures for key metrics (Total Revenue, Total Profit, Total Orders) to keep calculations accurate and dynamic.

## ✨ Advanced Features & Functionality
1. **Field Parameters:** Enabled dynamic metric switching so users can toggle charts between Revenue, Profit, and Orders using a single selection.
2. **Interactive Bookmarks:** Built custom view toggles to seamlessly switch visual layouts between "Revenue View" and "Profit View".
3. **Drill-Through Analysis:** Created a dedicated Product Detail page. Users can right-click any product to drill down into deep-dive performance trends.
4. **Custom Tooltips:** Implemented interactive report-page tooltips showing mini KPI summaries on hover.
5. **Dynamic Slicers:** Configured multi-select filters for Region, Category, and Date ranges for real-time data slicing.

## 🛠️ Tech Stack
* **BI Tool:** Power BI Desktop
* **Calculations:** DAX (Data Analysis Expressions)
* **Data Modeling:** Star Schema, Power Query
* **Version Control:** Git & GitHub

## 📸 Dashboard Screenshots
*(You can add screenshots of your dashboard inside a `Screenshots/` folder in your repository and display them here)*
