# Ferns and Petals Sales Analysis using Excel

## Overview
This project focuses on performing an end-to-end **sales analysis** for *Ferns and Petals*, an online gifting platform. The goal was to explore and analyze sales performance, customer behavior, and product trends using **Excel’s advanced data analysis and visualization tools**.

This was a **guided project** designed to strengthen data analytics skills, from raw data cleaning to dashboard creation and insights presentation.

---

## Project Objectives
- Analyze sales performance, revenue trends, and customer purchasing behavior.  
- Identify top-performing products, categories, and cities.  
- Evaluate order and delivery patterns to improve operational efficiency.  
- Create an interactive dashboard summarizing business insights.

---

## Tools and Techniques Used
- **Microsoft Excel**
  - Power Query Editor (for ETL: Extract, Transform, Load)
  - Power Pivot (for Data Modeling and DAX Calculations)
  - Pivot Tables and Charts (for Analysis and Visualization)
  - Slicers and Timelines (for Interactivity)
- **AI Summary (Executive Summary)** for concise project overview

---

## Dataset Description
The dataset simulates business data for *Ferns and Petals* and contains the following files:

| File | Description |
|------|--------------|
| `customers.csv` | Customer details including ID, Name, City, Gender, and Contact Information |
| `orders.csv` | Order transactions with product details, dates, quantities, and occasions |
| `products.csv` | Product catalog with category, price, and description information |

---

## Project Workflow

### 1. Data Extraction and Loading
- Loaded multiple CSV files using **Power Query Editor**.
- Combined data by folder connection for automatic updates.
- Added each dataset as a separate table and loaded to the Excel Data Model.

### 2. Data Cleaning and Transformation
Performed in Power Query:
- Removed duplicates and validated primary keys.
- Checked and handled null values.
- Standardized data types (converted contact numbers to text).
- Extracted useful fields such as:
  - Month and Hour from date and time columns.
  - Order-to-Delivery duration (difference in days).
- Merged tables to calculate total **Revenue** (`Price × Quantity`).
- Removed unnecessary columns (e.g., address, description).

### 3. Data Modeling
- Established relationships among tables using primary and foreign keys:
  - `Customer_ID` and `Product_ID` linked across datasets.
- Created calculated columns using **DAX**:
  - `Revenue_p_q` (Revenue per order)
  - `Order_Day_Name` (Day of order)
- Enabled Power Pivot for efficient modeling and calculations.

### 4. Data Analysis
Conducted multiple analyses using pivot tables to answer key business questions:
1. Total Revenue
2. Average Order and Delivery Time
3. Monthly Sales Trends
4. Top Products by Revenue
5. Customer Spending Patterns
6. Category-wise Sales Performance
7. Top Cities by Number of Orders
8. Correlation between Quantity and Delivery Time
9. Revenue by Occasion
10. Product Popularity by Occasion

---

## Dashboard Highlights
Developed an **interactive Excel dashboard** showcasing:
- Monthly and category-wise revenue trends.
- Top-performing products and cities.
- Key metrics: Total Revenue, Average Delivery Time, and Total Orders.
- Slicers and timelines for dynamic filtering.
- Clean, professional visual design using consistent themes and color schemes.

---

## Key Insights
- Seasonal and occasion-based spikes were identified in sales.
- Certain product categories dominated revenue across top cities.
- Delivery times showed variation depending on order size and occasion.
- Customer spending patterns helped identify high-value segments.

---

## Learnings
Through this project, I gained practical experience in:
- Using **Power Query** for end-to-end ETL operations.
- Building relationships and DAX formulas in **Power Pivot**.
- Designing a structured and interactive **Excel dashboard** for decision-making.
- Deriving actionable business insights from real-world-style data.


---

## Conclusion
This guided Excel project demonstrates the complete process of **data analysis — from data cleaning and modeling to dashboard visualization and insight generation.** It showcases how Excel can be effectively used for business analytics without relying on external BI tools.

---

**Author:** Mounika Seelam  
**Tools Used:** Microsoft Excel, Power Query, Power Pivot  
**Project Type:** Guided Data Analytics Project
