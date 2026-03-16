Drone Strike Analysis Dashboard

An end-to-end data analytics project analyzing drone strike data using Python, MySQL, and Power BI.
The project demonstrates data cleaning, data modeling, KPI analysis, and interactive dashboard reporting.

Project Overview

This project explores drone strike trends, casualties, and target groups through an interactive Power BI dashboard.

The workflow includes:

Raw Data → Python Data Processing → MySQL Data Model → Power BI Dashboard

The goal is to transform raw data into meaningful business insights and KPI metrics.

Tools & Technologies

Python (Pandas, SQLAlchemy)

MySQL

Power BI (DAX)

Jupyter Notebook

Data Modeling

A star schema data model was created in MySQL.

Fact Table
fact_strikes
Dimension Tables
dim_country
dim_president
dim_attack_type
dim_target_group
dim_target_type
dim_date

A reporting view was also created for Power BI:

vw_strikes_powerbi
Key Dashboard KPIs

The Power BI dashboard includes:

Total Strikes

Total Killed

Total Civilians

Total Injured

Dashboard Insights

The dashboard analyzes:

Drone strike trends over time

Strike distribution by president

Casualties by target group

Attack type distribution

Interactive filtering with slicers

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
Author

Dinesh Kumar Muthusamy

Data Analyst | BI Analyst
SQL • Power BI (DAX) • Python • MySQL • Data Modeling

LinkedIn:
https://www.linkedin.com/in/dinesh-kumar-muthusamy-856399333
