**Business Sales Dashboard – Global Sales Performance**
Future Interns – Data Science & Analytics (Task 1)

**Project Objective**

The objective of this project is to analyze global e-commerce data and uncover insights about best-selling products, top revenue-generating regions, customer distribution, quantity trends, and product demand patterns.
The project uses Power BI, Power Query, and DAX to build an interactive business dashboard.

Dashboard Features

1.KPI Cards

Total Sales

Total Quantity

Customer Count

Product Count

2.Product and Customer Analysis

Customer Count by Country

Customer Count by Product Description

Quantity Sold by Country

Product Frequency by Region

3.Revenue Analysis

TreeMap: Total Sales by Country and Product

Bar and Column Charts: Quantity and Sales trends

Gauge: Total Sales Tracking

4.Summary Table

Country-wise Quantity

Total Sales

Customer Count

Product Diversity

**Tools and Technologies**

Power BI Desktop

Power Query

DAX

Excel / CSV Dataset

Data Cleaning and Preparation
Performed using Power Query:

Removed null values and duplicates

Filtered invalid entries (Quantity less than or equal to 0, UnitPrice less than or equal to 0)

Corrected data types

Created calculated column Price = Quantity * UnitPrice

Loaded the clean dataset into Power BI

**DAX Measures**
Total Sales = SUM(Orders[Price])
Total Quantity = SUM(Orders[Quantity])
Customer Count = DISTINCTCOUNT(Orders[CustomerID])
Product Count = DISTINCTCOUNT(Orders[Description])

Repository Structure
FUTURE_DS_01.pbix – Power BI dashboard
dataset.csv or ecommerce.xlsx – Dataset used
Screenshots folder – Dashboard screenshots
README.txt – Documentation

**Key Insights**

The United Kingdom shows the highest sales and customer activity.

Some products dominate sales across multiple countries.

Customer concentration is highest in a few regions, while smaller countries contribute moderate but consistent numbers.

Certain products have strong multi-country demand, showing their global popularity.

The business heavily depends on a small number of top-performing products.

**Conclusion**

This dashboard provides a full overview of global sales performance and helps in understanding product performance, customer purchasing patterns, and regional contributions.
The project can be extended with time-series analysis, forecasting, profit metrics, segmentation, or geospatial visuals.
