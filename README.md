🛍️ Customer Shopping Behavior Analysis

A complete data analytics project including Python EDA, data cleaning, SQL analysis, and an interactive Power BI dashboard.

📌 Overview

This project analyzes customer shopping behavior to uncover trends, identify purchasing patterns, and generate actionable insights.
The workflow includes:

Loading and exploring a dataset in Python

Performing EDA and data cleaning

Executing analytical queries in MySQL

Designing an interactive Power BI dashboard

Presenting insights and business recommendations

📂 Dataset

File: customer_shopping_behavior.csv
The dataset includes:

Customer demographics

Shopping preferences

Purchase details (category, amount, payment method, etc.)

Store-related information

The dataset was used for exploratory analysis, transformations, and dashboard development.

🛠️ Tools & Technologies
Area	Tools Used
Programming	Python (Pandas, NumPy, Matplotlib, Seaborn)
Data Cleaning & EDA	Jupyter Notebook
Database	MySQL Server
Visualization	Power BI
Files Included	Customer_Shopping_Behavior_Analysis.ipynb, customer_shopping_behavior.csv, customer_behavior_dashboard.pbix
🧪 Project Steps
1. Load Dataset in Python

Imported the CSV file using Pandas

Performed initial inspection (shape, summary statistics, missing values)

2. Exploratory Data Analysis (EDA)

Visualized key variables (age, gender, category preference, purchase amount)

Analyzed customer segments

Identified spending patterns and seasonal trends

3. Data Cleaning

Handled missing values

Removed outliers (where necessary)

Fixed inconsistent categories and data types

Created engineered features for deeper analysis

4. SQL Analysis (MySQL)

Executed SQL queries to:

Summarize purchasing trends

Find top-selling product categories

Identify high-value customer groups

Analyze payment method patterns

5. Power BI Dashboard

Using cleaned and enriched data, the dashboard includes:

Customer demographics breakdown

Sales trends & category performance

Payment method insights

Interactive filters for deeper exploration

Dashboard file: customer_behavior_dashboard.pbix

📊 Dashboard Preview

Key visuals include:

Donut charts for demographic distribution

Line and bar charts for sales trends

Category-wise revenue visualization

Slicers for age group, gender, category, and payment method

📈 Results & Insights

Some high-level findings include:

Identification of top-spending customer segments

Most profitable product categories

Payment preferences by demographic group

Peak shopping times and behaviors

These insights can help businesses optimize inventory, pricing strategies, and customer targeting.

▶️ How to Run This Project
1. Run the Python Notebook

Install required libraries:

pip install pandas numpy matplotlib seaborn


Open Customer_Shopping_Behavior_Analysis.ipynb in Jupyter

Run the cells to reproduce EDA and cleaning steps

2. Load Data into MySQL

Create a new database

Import customer_shopping_behavior.csv

Run the SQL queries included in the project for analysis

3. Open the Power BI Dashboard

Open customer_behavior_dashboard.pbix in Power BI Desktop

Refresh data if needed

Explore the interactive visuals
