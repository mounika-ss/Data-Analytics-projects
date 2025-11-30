# Sales Analysis Using Excel (Guided Project)

## Overview
This project focuses on performing an end-to-end **sales analysis** for *Ferns and Petals*, an online gifting platform. The goal was to explore and analyze sales performance, customer behavior, and product trends using **Excel’s advanced data analysis and visualization tools**.

This was a **guided project** designed to strengthen data analytics skills, from raw data cleaning to dashboard creation and insights presentation.

---

## Executive Summary

The Ferns and Petals Sales Analysis project aimed to perform a complete business analysis using Microsoft Excel to understand key sales trends, customer behavior, and operational performance.
The dataset contained customer, order, and product information, enabling analysis from multiple perspectives—such as revenue, order frequency, product popularity, and delivery timelines.

The project followed an end-to-end data analytics workflow:

- Data Extraction and Cleaning: Using Power Query Editor, raw CSV files were imported, cleaned, and standardized. This included removing duplicates, checking for null values, converting data types, and creating additional columns such as month, day, and delivery duration.

- Data Modeling: Relationships were established between tables (Customers, Orders, and Products) using Power Pivot to create a robust data model. Calculated columns and DAX formulas were added to derive insights such as revenue per order and day of the week.

- Data Analysis: Multiple pivot tables were created to answer business questions such as:
  - Total and average revenue
  - Monthly sales performance
  - Top products and cities by orders
  - Customer spending patterns
  - Revenue variations across occasions
  - Relationship between order quantity and delivery time

- Dashboard Development: An interactive Excel dashboard was designed to present key insights visually. It includes dynamic slicers, timelines, and KPIs (total orders, average delivery time, and revenue). The dashboard provides a concise view for business decision-making.


Key Findings:

- Sales were highly influenced by special occasions and seasonal demand.
- Certain product categories generated higher revenue consistently across top cities.
- Customers from metropolitan cities contributed the most to total sales.
- Average delivery time and order quantity had minimal correlation, indicating efficient logistics handling.
- The interactive dashboard helps quickly identify performance trends and focus areas for improvement.

Outcome:
This guided project strengthened skills in data cleaning, modeling, visualization, and business interpretation using Excel. It demonstrates the ability to transform raw business data into meaningful insights and present them effectively through a professional dashboard.

---

## Project Objectives
- To perform data extraction, cleaning, and transformation using Power Query.  
- To create relationships and data models using Power Pivot.  
- To analyze sales performance and customer behavior.  
- To calculate key performance metrics such as total revenue, average spend, and delivery time.  
- To visualize business insights using Excel dashboards.

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
| `customers.csv` | Customer_ID, Name, City, Contact_Number, Email, Gender, Address |
| `orders.csv` | Order_ID, Customer_ID, Product_ID, Quantity, Order_Date, Order_Time, Delivery_Date, Delivery_Time, Location, Occasion |
| `products.csv` | Product_ID, Product_Name, Category, Price (INR), Occasion, Description |

---

## Project Workflow

### 1. Data Extraction and Loading
- Imported multiple CSV files using the “Get Data → From Folder” option.  
- Used Power Query to consolidate the datasets and prepare them for transformation.
- Combined data by folder connection for automatic updates.
- Added new queries and renamed tables for better readability.
- Added each dataset as a separate table and loaded to the Excel Data Model.

### 2. Data Cleaning and Transformation
Performed in Power Query:
- Checked and removed duplicates and null values.  
- Verified and corrected data types for each column.  
- Converted the contact number column to text for clear formatting.  
- Extracted month and hour from order and delivery date-time fields.  
- Calculated delivery difference (order to delivery days).  
- Merged the “Orders” and “Products” tables using Product_ID to add price information.  
- Created a new revenue column as (`Price × Quantity`).
- Removed unnecessary columns such as description, address, email, and contact number.

### 3. Data Modeling (Power Pivot)
- Loaded cleaned tables into Excel Data Model.  
- Established relationships between fact and dimension tables using primary and foreign keys.  
- Created calculated columns using DAX formulas such as:
  - `Revenue_p_q = [Price] * [Quantity]`
  - `Order_Day_Name = FORMAT([Order_Date], "DDDD")`
- Built measures to calculate key metrics like total revenue and average delivery time.

### 4. Data Analysis
Conducted multiple analyses using pivot tables to answer key business questions:
- Total revenue and total orders  
- Average order-to-delivery time  
- Monthly sales trends  
- Top 5 products by revenue  
- Average customer spending (Patterns)
- Revenue comparison by category and occasion (Category-wise Sales Performance)
- Top 10 cities by orders  
- Correlation between quantity and delivery time  
- Product popularity by occasion
- Revenue by Occasion

---

## Dashboard Creation
- Created pivot tables and pivot charts based on the analysis.  
- Added KPI boxes showing total orders, total revenue, average delivery days, and average spend.  
- Used slicers for interactive filtering by occasion, month, and city.  
- Applied timeline filters for date-based analysis.  
- Customized dashboard layout with consistent colors and titles for clarity.  
- Finalized the dashboard view and exported an image as the project summary.

---

## Key Insights
- Seasonal and occasion-based spikes were identified in sales.
- Certain product categories dominated revenue across top cities.
- Delivery times showed variation depending on order size and occasion.
- Customer spending patterns helped identify high-value segments.
- **Total Orders:** 1,000  
- **Total Revenue:** ₹35,20,984  
- **Average Order-Delivery Days:** 5.53 days  
- **Average Customer Spend:** ₹3,520.98  

**Top Insights**
- Anniversary occasion generated the highest revenue.  
- The “Colors” category contributed the most to total sales.  
- Top cities included Dhanbad, Imphal, and Kavali.  
- Highest sales were recorded during February.  
- Most orders were placed between 10 AM and 8 PM.
---

## Tools and Techniques Used
- **Microsoft Excel**
  - Power Query Editor (ETL – Extract, Transform, Load)
  - Power Pivot (Data Modeling and DAX)
  - Pivot Tables and Charts
  - Slicers and Timelines
  - Conditional Formatting and Data Visualization

## Learnings
Through this project, I gained practical experience in:
- Using **Power Query** for end-to-end ETL operations.
- Hands-on practice with Excel data modeling and Power Query
- Building relationships and DAX formulas in **Power Pivot**.
- Designing a structured and interactive **Excel dashboard** for decision-making.
- Experience in creating a complete dashboard workflow
- Deriving actionable business insights from real-world-style data.
- Understanding of business metrics and trend analysis.  
- Improved ability to build professional Excel dashboards from real-world datasets.


---

## Conclusion
This guided Excel project demonstrates the end-to-end data analysis process — from extracting and cleaning data to building a final interactive dashboard.  
It provided practical experience in using Excel for business intelligence and improved understanding of how data-driven insights can support decision-making.


---

**Author:** Mounika Seelam  
Data Analytics Enthusiast
**Tools Used:** Microsoft Excel, Power Query, Power Pivot  
**Project Type:** Guided Data Analytics Project

**From YT, Source Reference:** This project was completed as a guided practice based on the YouTube tutorial:
Link: [Watch on YouTube](https://www.youtube.com/watch?v=Wom-eVrE4RY)
