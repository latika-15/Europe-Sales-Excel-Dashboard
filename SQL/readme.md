# Europe Sales Analysis | Excel Dashboard + SQL (MySQL)

## Project Overview
This project presents an **end-to-end sales data analysis workflow**, starting with **Excel-based analysis and dashboarding**, followed by **SQL-based analysis using MySQL**.

The objective of the project is to:
- Understand sales performance
- Analyze revenue and profitability
- Explore trends across regions, products, channels, and time
- Demonstrate a structured analytics workflow used in real-world scenarios

The focus is on **data clarity, correct analysis, and business understanding**, rather than heavy visualization or automation.

---

## Analysis Workflow (IMPORTANT)

### 1️⃣ Excel Analysis (Initial Phase)
The raw dataset was first explored and cleaned in **Microsoft Excel** to:
- Understand data structure and quality
- Perform data cleaning and feature engineering
- Build Pivot Tables and an interactive dashboard
- Validate business metrics visually

### 2️⃣ SQL Analysis (Next Step)
After cleaning and analyzing the data in Excel:
- The cleaned dataset was exported as CSV
- Loaded into a **MySQL database**
- A fact table was designed
- SQL queries were written to validate insights and perform deeper analysis

This step-by-step workflow mirrors how analysts work in real organizations.

---

## Dataset Information
- **Source:** Kaggle  
- **Rows:** 1,331  
- **Columns:** 14 (raw data)  
- **Region Covered:** Europe  
- **Time Period:** 2010 – 2017 

## 🗄 SQL Database Design (MySQL)

### Database
CREATE TABLE fact_sales_orders (
    order_id INT,
    order_date DATE,
    ship_date DATE,
    region VARCHAR(50),
    country VARCHAR(50),
    item_type VARCHAR(50),
    sales_channel VARCHAR(20),
    order_priority VARCHAR(10),
    units_sold INT,
    unit_price DECIMAL(10,2),
    unit_cost DECIMAL(10,2),
    total_revenue DECIMAL(15,2),
    total_cost DECIMAL(15,2),
    total_profit DECIMAL(15,2),
    profit_margin DECIMAL(6,4),
    shipping_days INT
);

## Analysis Performed
- Revenue & Profit by Region
- Top 5 Countries by Profit
- Top 5 Countries by Revenue
- Product Profitability
- Online vs Offline Performance
- Shipping Efficiency by Order Priority
- High Volume but Low Profit Products

## Key Insights
- Certain product categories generate high revenue but lower profit margins
- Offline sales slightly outperform online sales in revenue contribution
- Sales peaked during mid-years and declined afterward
- Shipping time varies significantly by order priority
- Some high-volume products contribute negatively to overall profit

