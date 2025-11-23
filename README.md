# Behaviour-analysis-customer
Data analytics project showcasing customer behaviour analysis.The analysis was done using python,sql and the dashboard was made using power bi
📊 Data Analytics Project – End-to-End Workflow
📌 Overview

This project showcases a complete data analytics pipeline — from loading raw data in Python, performing EDA and cleaning, running SQL analysis on a PostgreSQL server, to building a Power BI dashboard and presenting insights through a Gamma-generated report and presentation.

The goal is to demonstrate strong analytical thinking, SQL proficiency, dashboard development, and storytelling skills using industry-standard tools.

📁 Dataset

Source: customer_shopping_behavior.csv (stored in C:\Users\acer\Downloads\New folder)


The dataset is used for Python EDA, SQL queries, and visualization in Power BI.

🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook / VS Code

PostgreSQL + pgAdmin

SQLAlchemy / psycopg2

Power BI Desktop

Gamma App (Report + Presentation)

Git / GitHub

🔍 Project Steps
1️⃣ Data Loading (Python)

Loaded the dataset using Pandas

Inspected structure, data types, and missing values

Saved intermediate cleaned version

2️⃣ Exploratory Data Analysis (EDA)

Summary statistics

Univariate & multivariate analysis

Outlier detection

Correlation analysis

Data visualizations (histograms, heatmaps, boxplots)

3️⃣ Data Cleaning

Removed duplicates

Treated missing values

Standardized column names

Fixed incorrect data types

Exported cleaned dataset for SQL analysis

4️⃣ SQL Analysis (PostgreSQL)

Created PostgreSQL database & table

Loaded cleaned CSV

Executed SQL queries including:

GROUP BY, ORDER BY

JOIN, CASE, IN

Aggregations (AVG, SUM, COUNT)

KPI calculations

Saved all queries in sql_queries.sql

5️⃣ Power BI Dashboard

Connected to cleaned dataset

Built interactive dashboard:

KPIs (totals, averages, rates)

Trend analysis

Category breakdown

Slicers & visual filters

Dashboard file: /dashboard/dashboard.pbix

6️⃣ Reports & Presentation (Gamma)

Created a structured analytics report

Designed a clean, concise presentation covering:

Project overview

Process

Insights

Recommendations

Files in /report/ folder

📈 Dashboard Preview

<img width="1337" height="773" alt="project" src="https://github.com/user-attachments/assets/d8f4a7bc-79e0-4940-bd60-897cd6053f97" />




▶️ How to Run This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/v-jsingh/Behavior-analysis-customer-SQL-Python-PowerBI.git
   cd customer-trends-data-analysis-SQL-Python-PowerBI
   ```
2. **Open Customer_Shopping_Behavior_Analysis.ipynb notebook**

    This file contains:

      - Data Import

      - Data exploration

      - Data cleaning

      - Connection to SQL Database
  
3. **Load the data from Python notebook into MySQL/PostgreSQL/MS SQL Server**

      - Create a database in SQL

      - Run Python code to load data into SQL database
  
      - Open **customer_behavior_sql_queries.sql**
  
      - Answer Business Questions using SQL Queries 
      
4. **Connect the SQL Database to Power BI**

      - Open **customer_behavior_dashboard.pbix**
   
      - Create interactive dashboard in Power BI
  
6. **Create Project Report and Presentation**

      - Create project report
   
      - Build presentation deck using Gamma AI
