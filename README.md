# Sales-Analysis-Project

### Dashboard Link : 
  https://app.powerbi.com/groups/me/reports/3b31c34d-db6f-4099-b477-a7faf216546a/a08ef5c1c508a0d2788f?experience=power-bi
  
## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Technologies Used](#technologies-used)
- [Data Cleaning and Feature Engineering](#data-cleaning-and-feature-engineering)
- [Exploratory Data Analysis and Visualization](#exploratory-data-analysis-and-visualization)
- [Conclusion](#conclusion)

## Project Overview

This project is a Sales Insights Dashboard built using Microsoft Power BI and SQL. It analyzes sales data from a computer hardware business to derive key business insights. The project demonstrates data cleaning, modeling, visualization, and dashboard creation to help stakeholders make informed decisions.

## Dataset Overview
The dataset used in this project contains sales transaction records from a computer hardware business. The key attributes include:

- Market Category
- Product Category & Sub-Category
- Customer Details
- Sales Revenue 
- Order Date & Region
  

## Technologies Used
- Power BI (for data visualization and dashboard development)
- SQL (for data extraction, transformation, and analysis)
- Power Query (for data transformation and cleaning)
- DAX (Data Analysis Expressions) (for calculated columns and measures)
- Excel/CSV (data source format)

## Data Cleaning and Feature Engineering
### Handling Missing Data :
- Identify and fill missing values where necessary.
- Remove duplicate records to maintain data integrity.
### Removing Invalid Entries :
- Filter out negative sales values and incorrect transaction entries.
- Ensure consistency in date formats and categorical values
### Feature Creation :
To enhance the analysis, additional features were derived:
- Computed Total Sales as Quantity * Unit Price.
- Extracted Year and Month from the order date for trend analysis.
- Used SQL queries to aggregate and filter data efficiently before loading into Power BI.

## Exploratory Data Analysis and Visualization
### Sales Performance Overview
- Analyzed overall revenue and quantity sold using key performance indicators (KPIs).
### Regional & Product Category Analysis
- Identified top-performing regions and best-selling product categories.
### Time-Based Trends
- Examined monthly and yearly sales trends using line and bar charts.
### Customer Segmentation
- Recognized high-value customers based on total spending and frequency of purchases.

## Conclusion
This project effectively demonstrates how SQL and Power BI can be leveraged to analyze and visualize sales data for actionable business insights. By integrating SQL for data extraction and transformation, Power BI for dynamic reporting, and DAX for advanced calculations, we built a robust sales insights dashboard
