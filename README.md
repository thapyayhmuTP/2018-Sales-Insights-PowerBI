# 2018-Sales-Insights-PowerBI
A data-driven Power BI report featuring sales insights, top cities, product trends, and seasonal analysis for 2018.


This project presents an interactive Power BI dashboard analyzing sales performance across products, cities, and payment modes for the year 2018. It highlights total revenue, profitability, product trends, and seasonal patterns to support business decision-making.


## Project Summary

This dashboard was built using two datasets: `Orders.csv` and `Details.csv`, linked via a one-to-many relationship on `Order ID`. A custom date table was generated using DAX (`CALENDARAUTO()`) to support time-based insights and trend analysis.

Key DAX measures:
- **Total Sales**  
- **Total Profit**  
- **Profit Margin (%)**  
- **Average Profit per Order**  
- **Monthly Sales**

Custom sorting and ranking logic (via `RANKX`) was implemented to identify top-performing cities and support visual clarity.

---

## Key Insights

- **Total Sales:** \$438K | **Profit:** \$37K | **Profit Margin:** 8.44%
- **Best-Selling Categories:** Electronics and Clothing lead in revenue.
- **Highest Profit Margins:** Clothing (9.2%) and Furniture (8.2%)
- **Top Cities by Sales:** Indore, Mumbai, Pune, Mathura, Bhopal
- **Payment Trends:** EMI was the most-used payment method (45.6%)
- **Seasonal Trends:** Sales peaked in **April** and **October**, dipped in **June** and **July**

---

## Features and Visuals

- Slicers for dynamic filtering (Month, Category, Sub-Category, City, Payment Mode)
- KPI cards for total sales, profit, and margin
- Bar charts for category-wise sales, quantity, and profit
- Sub-category breakdowns (Printers, Sarees top sales)
- Top 5 cities table (ranked using DAX logic)
- Monthly trend line chart for sales and profit
- Donut chart for payment mode distribution

---

## Tools & Techniques

- **Power BI Desktop**
- **DAX Measures & Calculated Columns**
- **Data Cleaning & Relationship Modeling**
- **Custom Date Table & Sorting Logic**
- **Interactive Visual Design**

---

## Team Collaboration

This dashboard was developed as part of a team project for **CPSC 510: Data Warehousing & Visualization** at the University of Niagara Falls.  
All team members contributed to **visual development** and **insight generation** collaboratively.

---

## Files Included

- `SalesInsights2018.pbix` – Full Power BI dashboard file
- `Images/dashboard.png` – Preview of final report
- `Details.csv` & `Orders.csv`

---

## Author

Tha Pyay Hmu   
