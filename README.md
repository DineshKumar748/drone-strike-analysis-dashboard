Drone Strike Analysis Dashboard

An end-to-end data analytics project analyzing drone strike operations using Python, MySQL, and Power BI.
The project demonstrates data cleaning, SQL data modeling (star schema), KPI reporting, and interactive dashboard development.

Project Overview

This project analyzes historical drone strike data to uncover trends, casualty statistics, and operational patterns through an interactive Power BI dashboard.

The workflow follows a typical data analytics pipeline:

Raw Dataset → Python Data Processing → MySQL Data Modeling → Power BI Dashboard

The goal is to transform raw operational data into clear insights and decision-support metrics.

Tools & Technologies

Python (Pandas, SQLAlchemy)

MySQL

Power BI (DAX)

Jupyter Notebook

Data Source

The dataset used in this project comes from the Drone Wars Database.

Source:
https://dronewars.github.io/data/

The database aggregates information collected by the Bureau of Investigative Journalism on U.S. drone strike operations.

Data includes:

strike dates

location information

attack types

target groups

casualty estimates

Data Modeling

A star schema data model was implemented in MySQL to support efficient analytics.

Fact Table
fact_strikes
Dimension Tables
dim_country
dim_president
dim_attack_type
dim_target_group
dim_target_type
dim_date

A Power BI reporting view was created to simplify dashboard queries:

vw_strikes_powerbi
Dashboard KPIs

The dashboard highlights key performance metrics:

Total Strikes

Total Killed

Total Civilians

Total Injured

Dashboard Insights

The Power BI dashboard provides insights into:

strike trends over time

operational activity by U.S. president

casualty distribution by target group

strike distribution by attack type

interactive filtering through slicers

Dashboard Preview

MySQL Data Model
Database Schema

Fact Table Structure

Power BI Reporting View

Repository Structure
Drone_Strike_Dashboard.pbix
drone_strike_data_pipeline.ipynb
DroneWarsData.csv
dashboard_overview.png
mysql_database_schema.png
mysql_fact_table.png
mysql_powerbi_view.png
Skills Demonstrated

Data Cleaning and Transformation

SQL Data Modeling (Star Schema)

KPI Dashboard Development

Power BI Data Visualization

DAX Measures

End-to-End Data Analytics Workflow

Author

Dinesh Kumar Muthusamy

Data Analyst | Business Intelligence | Power BI | SQL | Python | MySQL | Data Modeling

LinkedIn:
https://www.linkedin.com/in/dinesh-kumar-muthusamy-856399333
