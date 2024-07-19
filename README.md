# Patient21_Analytics

# Project Overview
This project aims to estimate the revenue and the number of unique patients expected in 2023 for Patient21's clinics. The analysis considers the launch of two new clinics in March and July 2023, alongside the operation of the two existing clinics. The approach involves using SQL for data extraction, and Python for analysis and forecasting, with the results presented in a PDF format.

# Files Included
project_report.pdf: The main report detailing the analysis, methodology, and conclusions.
p21_by_intern_test_appointments.csv: The dataset containing appointment information.
p21_bi_intern_test_revenues.csv: The dataset containing revenue information.

# Analysis Steps
Data Ingestion and Initial Observations:

Imported the CSV files into DBeaver to understand the schema

Observed that appointment_id is the primary key in both tables, allowing for a seamless join.
Data Preparation:

- Checked for any discrepancies or null values in the datasets.
- Joined the two tables on appointment_id.
- 
Exploratory Data Analysis (EDA):

- Visualized data to understand patterns and trends using Tableau.
- Noted significant drops in revenue and unique patient visits during weekends.
- Identified that Clinic 2 had more unique patients but Clinic 1 had comparable revenue, suggesting frequent revisits.

# Forecasting Methodology:

- Forecasted revenue using linear regression and trend analysis.
- Predicted unique patients using the Facebook Prophet model.
- Assumptions were made based on the analysis, such as clinic types and their locations.

# Revenue and Unique Patients Forecast for 2023:

- Projected revenue by analyzing trends from the existing clinics and scaling the results for the new clinics.
- Calculated unique patient visits by predicting daily visits and scaling for the new clinics.

# Tools Used
- SQL: For data extraction and initial data analysis.
- Python: For forecasting using linear regression and the Facebook Prophet model.
- Tableau: For data visualization and identifying patterns.
- Excel: For initial trend analysis and calculations.

# Key Findings
The total expected revenue for 2023 is approximately $4,033,864.7.
The total number of unique patients expected in 2023 is approximately 13,249.
