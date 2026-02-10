
# Europe Sales Performance Dashboard (Excel)

## Project Overview
This project demonstrates an end-to-end **Excel-based data analysis and dashboarding workflow** using a real-world sales dataset from Kaggle.  
The goal was to clean raw data, engineer meaningful features, analyze sales performance, and present insights through an interactive Excel dashboard.

The project focuses on **clarity, correctness, and business understanding**, rather than heavy visual design.

---

## Dataset Information
- **Source:** Kaggle  
- **Rows:** 1,330 
- **Columns:** 14 (raw data)  
- **Region Covered:** Europe  
- **Time Period:** 2010 – 2017  

The raw dataset contains order-level sales transactions including region, item type, sales channel, order and ship dates, revenue, cost, and profit.

---

## Tools & Technologies Used
- Microsoft Excel  
  - Power Query  
  - Pivot Tables  
  - Pivot Charts  
  - Slicers  
- Excel Formulas  
- Basic Data Modeling

---

## Data Cleaning & Preparation
The following data preparation steps were performed:

- Converted text-based **Order Date** and **Ship Date** into proper date formats
- Handled date format inconsistencies (MM/DD/YYYY)
- Corrected data types and formats for numeric and date columns
- Ensured consistency for use in Pivot Tables and dashboards

---

## Feature Engineering
New columns created to support analysis:

- Order Year, Month, Day  
- Ship Year, Month, Day  
- Profit Margin Percentage  
- Revenue per Unit  

These features enabled time-based analysis, profitability comparison, and performance evaluation.

---

## Analysis Performed Using Pivot Tables
Key analyses included:

- Total Revenue and Total Profit by Region
- Sales Channel comparison (Online vs Offline)
- Profit contribution by Item Type
- Year-wise sales trend
- Average Shipping Days by Order Priority
- Validation tables to support dashboard insights

---

## Dashboard Overview
An interactive Excel dashboard was created with:

- **3 Pivot Charts**
  - Total Profit by Item Type
  - Total Revenue & Profit By Region
  - Sales Distribution by Channel
  - Year-wise Sales Trend
- **Slicers**
  - Order Year
  - Sales Channel
  - Item Type

The dashboard allows users to dynamically filter and explore sales and profitability insights.

---

## Key Insights
- Cosmetics and Office Supplies contribute significantly to total profit
- Offline sales slightly outperform online sales in revenue contribution
- Sales peaked around 2012–2014, followed by a gradual decline
- Shipping time varies noticeably by order priority

---

## Project Screenshots
Screenshots of the dashboard and pivot tables are available in the `/Screenshots` folder.

---

## How to Use This Project
1. Download the repository
2. Open `Europe_Sales_Dashboard.xlsx`
3. Use slicers to explore data interactively
4. Review pivot tables for detailed validation

---

## Skills Demonstrated
- Data cleaning in Excel
- Date handling and transformation
- Feature engineering
- Pivot Tables & Pivot Charts
- Dashboard design principles
- Business-oriented data analysis

---

## Future Improvements
- Add KPI cards (Revenue, Profit, Margin)
- Create Top/Bottom 5 product analysis
- Migrate the dashboard to Power BI
- Automate refresh using Power Query

---

## Author
**Latika Tewari**  
Aspiring Data Analyst  

GitHub: https://github.com/latika-15
