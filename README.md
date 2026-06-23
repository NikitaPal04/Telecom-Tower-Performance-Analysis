# Telecom Tower Performance Analysis

## Project Overview

This project analyzes the performance of telecom towers using Python and data analytics techniques. The objective is to identify high-performing and underperforming towers, evaluate engineer performance, estimate maintenance budgets, and generate actionable business recommendations.

## Business Problem

Telecom companies need to monitor tower performance continuously to ensure reliable network coverage and customer satisfaction. Poor signal strength, high downtime, and excessive customer complaints can negatively impact service quality.

This project helps management identify:

* Best and worst performing cities
* Best and worst engineers
* High-risk towers
* Towers due for maintenance
* Upgrade requirements
* Estimated maintenance budget

## Dataset Information

The dataset was manually created to simulate real-world telecom tower operations and contains information such as:

* Tower ID
* City
* Engineer
* Signal Strength
* Downtime Hours
* Customer Complaints
* Maintenance Cost
* Last Service Date

## Data Cleaning

The following data cleaning steps were performed:

* Handled missing values
* Standardized text fields
* Corrected inconsistent engineer names
* Checked for duplicate records
* Verified data types

## Feature Engineering

A custom Performance Score was created using:

Performance Score = Signal Strength - Downtime Hours - (Customer Complaints / 2)

Additional indicators were generated to identify:

* High-risk towers
* Towers requiring upgrades
* Maintenance priorities

## KPIs Generated

* Best City
* Worst City
* Best Engineer
* Worst Engineer
* Top 5 Towers
* Bottom 5 Towers
* High Risk Towers
* Maintenance Budget
* Towers Due for Service
* Upgrade Recommendations

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Key Insights

* Identified top-performing cities based on average performance score.
* Ranked towers according to operational efficiency.
* Evaluated engineer performance.
* Estimated future maintenance requirements.
* Flagged towers that require immediate attention.

## Project Structure

Telecom-Tower-Performance-Analysis

├── notebooks

│   ├── Telecom_Tower_Performance_Analysis.ipynb

│   └── README.md

├── README.md

├── LICENSE

└── .gitignore

## Future Improvements

* Interactive Power BI Dashboard
* SQL Database Integration
* Automated KPI Reporting
* Predictive Maintenance Model

## Author

Nikita Pal

Graduate Engineer 

Data Analytics & Environmental Engineering Enthusiast
