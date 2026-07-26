# Retail Sales Analytics & Business Intelligence Dashboard

An end-to-end data analytics project that analyzes retail sales performance using **SQL, Python, and Power BI**. The objective is to transform transactional sales data into actionable business insights that support strategic decision-making, identify profit drivers, and highlight opportunities for operational improvement.


<p align="center">
  <img src="images/executive_overview.png" alt="Sales Analysis Dashboard" width="900">
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Graphics-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

</p>


---

## Project Overview

Retail organizations generate vast amounts of transactional data every day. However, data alone does not create value unless it is transformed into meaningful business insights.

This project demonstrates a complete analytics workflow—from querying and cleaning raw sales data to building an interactive business intelligence dashboard. The analysis focuses on understanding sales performance, profitability, customer purchasing patterns, regional performance, and the impact of discounting on profit.

The final deliverable is a multi-page Power BI dashboard designed to support business stakeholders in making informed, data-driven decisions.

---

## Business Problem

Management requires a clear understanding of:

- Which product categories generate the highest revenue and profit.
- Which regions contribute most to business performance.
- Whether discounting strategies improve or reduce profitability.
- Seasonal sales trends throughout the year.
- Which products and locations require management attention.

Without data-driven insights, strategic decisions regarding pricing, inventory, and regional investment become difficult.

---

## Project Objectives

This project aims to:

- Analyze historical retail sales performance.
- Identify key drivers of revenue and profitability.
- Evaluate the relationship between discounting and profit.
- Compare regional and product category performance.
- Build an interactive dashboard for executive decision-making.
- Provide actionable business recommendations based on the findings.

---

## Dataset

The project uses the **Sample Superstore** dataset, a widely used retail dataset containing transactional sales records.

The dataset includes information on:

- Orders
- Sales
- Profit
- Discounts
- Products
- Categories
- Customers
- States
- Regions
- Order Dates

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| SQL | Data exploration and business queries |
| Python | Data cleaning and exploratory data analysis |
| Pandas | Data manipulation |
| Matplotlib | Data visualization |
| SQLite | Database management |
| Power BI | Interactive dashboard development |

---

# Project Workflow

```
Raw Sales Data
        │
        ▼
SQL Data Exploration
        │
        ▼
Python Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Business Insights
        │
        ▼
Power BI Dashboard
        │
        ▼
Recommendations
```

---

# SQL Analysis

SQL was used to answer key business questions, including:

- Total sales generated
- Total profit
- Monthly sales performance
- Sales by region
- Profit by category
- Top-performing states
- Customer sales rankings
- Discount impact on profitability

These queries formed the analytical foundation for subsequent visualizations and dashboard development.

---

# Python Analysis

Python was used to:

- Clean and prepare the dataset
- Handle missing values
- Perform exploratory data analysis
- Aggregate sales metrics
- Generate supporting visualizations
- Export cleaned data for Power BI

---

# Power BI Dashboard

The final dashboard consists of four interactive reporting pages designed for business stakeholders.

---

## Executive Overview

![Executive Overview](images/executive_overview.png)

Provides high-level KPIs including Total Sales, Total Profit, Profit Margin, Average Discount, and monthly sales trends to support executive decision-making.

---

## Product Performance

![Product Performance](images/product_performance.png)

Evaluates product categories and sub-categories based on sales and profitability while illustrating how increasing discounts affect profit margins.

---

## Regional Performance

![Regional Performance](images/regional_performance.png)

Compares sales performance across regions and identifies the highest-performing states, helping management prioritize investment and operational focus.

---

## Insights & Recommendations

![Insights and Recommendations](images/insights_recommendations.png)

Summarizes the analytical findings and provides actionable recommendations to improve profitability, optimize discount strategies, and strengthen regional performance.

---

# Key Business Insights

The analysis revealed several important findings:

- Total sales exceeded **$2 million**, generating approximately **$286,000** in profit.
- Overall profit margin was approximately **12%**, indicating relatively thin profitability.
- Technology was the highest-performing product category in both sales and profit.
- Furniture generated strong revenue but significantly lower profitability.
- The **Tables** sub-category recorded negative profit, reducing overall business performance.
- Profit declined substantially when discounts exceeded approximately **15–20%**, suggesting aggressive discounting erodes profitability.
- The **West** and **East** regions achieved the strongest profit margins.
- Sales demonstrated seasonal patterns, with the highest monthly performance occurring during the fourth quarter.

---

# Business Recommendations

Based on the analysis, the following actions are recommended:

1. Review pricing and cost structures within the Furniture category, particularly the Tables sub-category.
2. Establish discount guidelines to minimize profit erosion while maintaining competitive pricing.
3. Increase investment in high-performing Technology products.
4. Prioritize expansion strategies in the West and East regions.
5. Prepare inventory and staffing for increased fourth-quarter demand.
6. Conduct further analysis of customer purchasing behavior to improve targeted marketing efforts.

---

# Repository Structure

```
retail-sales-analytics-dashboard/

│
├── data/
│   ├── raw_sales_data.csv
│   └── cleaned_sales_data.csv
│
├── notebooks/
│   └── retail_sales_analysis.ipynb
│
├── dashboard/
│   └── retail_sales_dashboard.pbix
│
├── images/
│   ├── executive_overview.png
│   ├── product_performance.png
│   ├── regional_performance.png
│   └── insights_recommendations.png
│
└── README.md
```

---

# Skills Demonstrated

This project demonstrates practical experience in:

- SQL querying
- Data cleaning
- Exploratory Data Analysis (EDA)
- Business Intelligence
- KPI development
- Dashboard design
- Data visualization
- Business storytelling
- Decision support analytics
- Power BI
- Python (Pandas & Matplotlib)

---

# Limitations

The analysis is subject to several limitations:

- The dataset represents historical transactional data and does not include customer demographics or marketing information.
- External factors such as inflation, competition, and supply chain disruptions were not considered.
- The dashboard focuses on descriptive analytics rather than predictive modeling.

---

# Future Enhancements

Future versions of this project may include:

- Customer segmentation using RFM analysis.
- Sales forecasting using time-series models.
- Predictive profit modeling with machine learning.
- Interactive drill-through functionality in Power BI.
- Additional DAX measures and advanced KPI tracking.
- Integration with cloud-based data sources.

---

Data Analyst | Python | SQL | Power BI

**Mubarik Wusa Manga**

I enjoy transforming raw data into actionable insights that support business decision-making.

Feel free to connect with me on LinkedIn or explore my other projects on GitHub.
GitHub: https://github.com/MaWusaM

LinkedIn: https://linkedin.com/in/Mubarik-Wusa-Manga-5439911b4 

---

