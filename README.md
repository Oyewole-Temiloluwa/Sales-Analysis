# Sales Analysis Project

## Project Overview

This project provides an in-depth analysis of the **Adventure Works Database** to deliver actionable insights into sales, customers, and products. The business requirements focused on creating visualizations under the following categories:
- **Sales Overview**
- **Customer Overview**
- **Product Overview**

### Objectives
- Clean and transform raw data extracted from the Adventure Works Database.
- Visualize key metrics to meet the business owner's requirements.
- Provide dashboards highlighting trends and insights.

---

## Data Sources and Transformation

### Data Sources
The project utilized the following tables from the Adventure Works Database:
- **DIM_Calendar**
- **DIM_Customer**
- **DIM_Product**
- **FACT_InternetSales**

### Data Transformation
Data cleaning and transformation were performed in **Microsoft SQL Server**, including:
- Standardizing data formats.
- Handling missing values.
- Joining tables for meaningful insights.

The transformed data was saved as **Excel files** for use in Power BI.

---

## Dashboards

### 1. Sales Overview
This dashboard highlights:
- Monthly sales trends.
- Total revenue by region.
- Sales contributions by product categories.

![Sales Overview Dashboard](Sales_Overview.jpg)

---

### 2. Customer Overview
This dashboard focuses on:
- Customer demographics and distribution.
- High-value customer segmentation.
- Sales trends by customer groups.

![Customer Overview Dashboard](Customer_Overview.jpg)

---

### 3. Product Overview
This dashboard covers:
- Best-selling products.
- Product category performance.
- Revenue generated by product lines.

![Product Overview Dashboard](Product_Overview.jpg)

---

## Tools and Technologies
- **SQL Server**: For data extraction, cleaning, and transformation.
- **Excel**: To store cleaned data for analysis.
- **Power BI**: For creating interactive visualizations and dashboards.

---

## Files in Repository

| File Name               | Description                                        |
|-------------------------|----------------------------------------------------|
| `DIM_Calendar.csv`      | Cleaned calendar data.                             |
| `DIM_Customer.csv`      | Cleaned customer data.                             |
| `DIM_Product.csv`       | Cleaned product data.                              |
| `FACT_InternetSales.csv`| Cleaned internet sales data.                       |
| `SalesBudget.xlsx`      | Budget data used for sales analysis.               |
| `Project.pbix`          | Power BI project file with the created dashboards. |

---

## How to Use

1. **Data Preparation**:
   - Use the provided `.sql` files to replicate the data cleaning process in SQL Server.

2. **Visualization**:
   - Open the `Project.pbix` file in Power BI to explore the dashboards.

3. **Customization**:
   - Modify the Power BI dashboards as needed to include additional insights or metrics.

---

## Acknowledgments

This project is based on the **Adventure Works Database** and demonstrates the use of data analysis and visualization tools for actionable business insights.
