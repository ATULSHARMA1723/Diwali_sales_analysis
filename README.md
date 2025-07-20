# Diwali Sales Analysis
This project performs an exploratory data analysis (EDA) of Diwali sales data to uncover valuable insights into customer behavior and purchasing trends during the Diwali festival season. It demonstrates skills in data cleaning, preprocessing, visualization, and drawing business-relevant insights using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

# Project Objective
To analyze Diwali sales transaction data in order to:

Understand customer demographics and buying behavior

Identify top-selling product categories and high-performing regions

Support business decisions for marketing and inventory planning during festive seasons

# Dataset Overview
File Name: Diwali Sales Data.csv

Size: ~11,000 rows

Features include:

Gender, Age Group, Marital Status

Occupation, State, Product Category, Product ID

Amount, Orders, Customer ID

Note: Some unnecessary or blank columns were removed during preprocessing.

# Tools and Libraries Used
Python 3.x

Pandas – data manipulation

NumPy – numerical operations

Matplotlib & Seaborn – data visualization

Jupyter Notebook – interactive development environment

# Key Steps Performed
Data Loading and Inspection

Read CSV file using pandas.read_csv()

Used .info(), .shape(), .head() to examine structure

Data Cleaning

Dropped irrelevant or empty columns like 'Status', 'unnamed1'

Removed rows with null values

Converted Amount column to integer for numerical operations

Exploratory Data Analysis (EDA)

Analyzed and visualized:

Gender-based spending

Age group-wise purchase patterns

Marital status and occupation influence on spending

State-wise and product category-wise performance

Visual tools used: bar charts, histograms, count plots, etc.

Data Visualization

Used seaborn and matplotlib to present data-driven insights

Created segment-wise and region-wise comparison charts

# Insights and Outcomes
Key findings from the analysis:

Major buyers were women aged 26–35, especially married professionals.

Top-performing states in terms of sales were Maharashtra, Karnataka, and Uttar Pradesh.

Most revenue came from product categories like Clothing and Electronics.

Customers from metro cities showed higher transaction volume.

Useful for targeted marketing, personalized promotions, and stock planning
