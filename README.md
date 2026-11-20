# SQL Data Analytics Project
A complete SQL-based data analytics project covering Exploratory Data Analysis (EDA) and advanced analytics, from initial database discovery to customer and product reporting.

The repository uses T-SQL and is organized as a repeatable workflow. Each script builds on the analysis concepts introduced by the previous one.

![Uploading SQL Project map.jpg…]


---------
# 🎯Overview
```
This project demonstrates how SQL can be used to understand a dataset,
answer business questions, identify trends, and create reporting views.
```
---
# ✨ The project is ready to the  answer questions such as:
```
    Which customers generate the most revenue?
    Which products have the highest sales?
    How do sales change over time?
    Which categories contribute the largest share of total revenue?
    How does current performance compare with previous periods?
    What customer segments exist in the data?
    Which products should receive more attention based on sales and performance?
```
----
# The workflow progresses through:
```
  ->Database and table exploration
  ->Dimension and measure analysis
  ->Date-range validation
  ->Ranking and magnitude analysis
  ->Trend and cumulative analysis
  ->Customer and product segmentation
  ->Final reporting queries
  ->Repository Structure.
```
---
# Repo contains:
```
SQL-Data-Analytics-Project/
├── datasets/
│   └── csv.files/                # Source CSV datasets
├── docs/
│   ├── SQL Project map.jpg       # Project architecture and analysis roadmap
│   ├── Dimension & Measure.jpg
│   ├── Notion Roadmap.pdf
│   └── planning documents
├── scripts/
│   ├── 00_init_database.sql
│   ├── 01_database_exploration.sql
│   ├── ...
│   ├── 12_report_customers.sql
│   └── 13_report_product.sql
└── LICENSE
```
---
# Analysis Workflow
 🔑 Key Concepts Covered:                   
```
  00_init_database.sql	             Creates and initializes the database objects
  01_database_exploration.sql	       Examines databases, tables, columns, and schemas
  02_dimensions_exploration.sql	     Identifies dimension values and categorical fields
  03_date_range_exploration.sql	     Determines the available analysis period
  04_measures_exploration.sql	       Calculates key summary measures
  05_magnitude_analysis.sql	         Compares values across categories
  06_ranking_analysis.sql	           Identifies top and bottom records
  07_change_over_time_analysis.sql	 Studies trends and changes over time
  08_cumulative_analysis.sql	       Calculates running totals and cumulative measures
  09_performative_analysis.sql	     Measures performance against benchmarks
  10_part_to_whole_analysis.sql    	 Calculates category contributions to totals
  11_data_segmentation.sql	         Groups records by meaningful business segments
  12_report_customers.sql         	 Produces the customer-level report
  13_report_product.sql	             Produces the product-level report

```
---
# 📄Documentation
The docs directory contains supporting project materials:

SQL project roadmap
Data analytics workflow diagram(draw.io)
<img width="1366" height="768" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/3ef22283-60b9-414a-b7ab-4a189d06deb6" />

Dimension and measure reference
Project planning information
Notion roadmap and project planning exports


[![Built with Data With Baraa](https://img.shields.io/badge/Built_with-Data_With_Baraa-F5B301?style=for-the-badge)](https://github.com/DataWithBaraa/sql-data-warehouse-project)
