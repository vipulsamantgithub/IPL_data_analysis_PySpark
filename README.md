# IPL Data Analysis using PySpark, AWS S3, and Databricks
This project focuses on end-to-end data engineering and analysis of Indian Premier League (IPL) data using PySpark on Databricks, with data stored on AWS S3. The goal is to extract meaningful insights from match and player performance data using scalable big data tools and practices.

# 🔧 Tools & Technologies Used
PySpark: For scalable data processing and transformations

Databricks: Interactive workspace for running PySpark notebooks

AWS S3: Storage layer for IPL datasets (CSV files)

Spark SQL: For structured querying and aggregations

Matplotlib / Plotly (optional): For data visualization

# 📌 Project Workflow
Data Collection

IPL datasets (match-level, ball-by-ball, player info) stored in AWS S3 buckets.

ETL Process with PySpark

Loaded raw CSV files from S3 using Spark.

Cleaned and transformed datasets (e.g., renaming columns, handling nulls).

Performed joins across tables for consolidated analysis.

Exploratory Data Analysis

Powerplay analysis: most economical bowlers

Toss impact: correlation between toss winner and match winner

Team and player performance over seasons

Visualized insights using Spark SQL + optional Pandas/Plotly

# 🔍 Key Insights
Identified top-performing bowlers in powerplay overs based on average runs per ball and wicket count.

Analyzed how toss outcomes influence match results.

Aggregated team-wise performance metrics across seasons.

