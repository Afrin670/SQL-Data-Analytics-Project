SQL Data Analytics Project
A complete SQL-based data analytics project covering Exploratory Data Analysis (EDA) and advanced analytics, from initial database discovery to customer and product reporting.

The repository uses T-SQL and is organized as a repeatable workflow. Each script builds on the analysis concepts introduced by the previous one.

![T-SQL](https://img.shields.io/badge/T--SQL-100%25-blue) ![License](https://img.shields.io/badge/License-MIT-green)

Overview
This project demonstrates how SQL can be used to understand a dataset, answer business questions, identify trends, and create reporting views.

The workflow progresses through:

Database and table exploration
Dimension and measure analysis
Date-range validation
Ranking and magnitude analysis
Trend and cumulative analysis
Customer and product segmentation
Final reporting queries
Repository Structure
Text
SQL-Data-Analytics-Project/
├── datasets/
│   └── csv.files/             # Source CSV datasets
├── docs/
│   ├── SQL Project map.jpg    # Project architecture and analysis roadmap
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
Analysis Workflow
Script	Purpose
00_init_database.sql	Creates and initializes the database objects
01_database_exploration.sql	Examines databases, tables, columns, and schemas
02_dimensions_exploration.sql	Identifies dimension values and categorical fields
03_date_range_exploration.sql	Determines the available analysis period
04_measures_exploration.sql	Calculates key summary measures
05_magnitude_analysis.sql	Compares values across categories
06_ranking_analysis.sql	Identifies top and bottom records
07_change_over_time_analysis.sql	Studies trends and changes over time
08_cumulative_analysis.sql	Calculates running totals and cumulative measures
09_performative_analysis.sql	Measures performance against benchmarks
10_part_to_whole_analysis.sql	Calculates category contributions to totals
11_data_segmentation.sql	Groups records by meaningful business segments
12_report_customers.sql	Produces the customer-level report
13_report_product.sql	Produces the product-level report
Key Concepts Covered
Dimension and measure identification
Data profiling and metadata discovery
Aggregate functions
Grouping and filtering
Window functions
Ranking with ROW_NUMBER, RANK, and DENSE_RANK
Cumulative calculations
Running totals
Period-over-period changes
Contribution and percentage analysis
Customer segmentation
Product performance reporting
Reporting-ready SQL views or query outputs
Prerequisites
To run the project, you need:

SQL Server
SQL Server Management Studio (SSMS), Azure Data Studio, or another T-SQL-compatible client
Permission to create or modify a database
The CSV or source data available in the datasets directory
Getting Started
1. Clone the repository
bash
git clone https://github.com/Afrin670/SQL-Data-Analytics-Project.git
cd SQL-Data-Analytics-Project
2. Open a SQL client
Connect to your SQL Server instance.

3. Initialize the database
Run:

Text
scripts/00_init_database.sql
This script prepares the database for the remaining analysis.

4. Run the analysis scripts
Execute the scripts sequentially:

Text
01_database_exploration.sql
02_dimensions_exploration.sql
03_date_range_exploration.sql
04_measures_exploration.sql
05_magnitude_analysis.sql
06_ranking_analysis.sql
07_change_over_time_analysis.sql
08_cumulative_analysis.sql
09_performative_analysis.sql
10_part_to_whole_analysis.sql
11_data_segmentation.sql
12_report_customers.sql
13_report_product.sql
Run the scripts in numerical order because later reports and analyses may depend on the database structures and fields created earlier.

Example Analyses
Depending on the source dataset, the project can answer questions such as:

Which customers generate the most revenue?
Which products have the highest sales?
How do sales change over time?
Which categories contribute the largest share of total revenue?
How does current performance compare with previous periods?
What customer segments exist in the data?
Which products should receive more attention based on sales and performance?
Documentation
The docs directory contains supporting project materials:

SQL project roadmap
Data analytics workflow diagram
Dimension and measure reference
Project planning information
Notion roadmap and project planning exports
These resources help explain the analytical approach and provide a high-level view of the project structure.

Dataset
Source data is stored in:

Text
datasets/csv.files/
Review the initialization script and the dataset contents before running the project to confirm the required database, schema, and table names.

Intended Audience
This repository is useful for:

SQL and T-SQL learners
Aspiring data analysts
Students studying exploratory data analysis
Beginners developing customer or product reporting skills
Anyone learning to structure SQL projects from discovery through reporting
License
This project is available under the MIT License.

Acknowledgement
This project is based on the SQL analytics learning approach by Data With Baraa.







[![Built with Data With Baraa](https://img.shields.io/badge/Built_with-Data_With_Baraa-F5B301?style=for-the-badge)](https://github.com/DataWithBaraa/sql-data-warehouse-project)
