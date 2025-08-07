# IBM-HR-Analytics-Employee-Attrition-Performance-in-pandas

This project aims to explore, clean, and analyze an employee attrition dataset to uncover insights that can help organizations reduce employee turnover and improve job satisfaction.

## Problem Statement
Employee attrition (voluntary or involuntary) is a major concern for organizations as it affects productivity, morale, and recruitment costs. This project investigates:

Why employees leave their companies.

Which features influence attrition.

What actionable insights can help in retention strategies.

## Objectives

Perform data cleaning and preprocessing on a real-world HR dataset.

Handle missing values, incorrect data types, and duplicates.

Use Indexing, Filtering, and GroupBy Aggregations to analyze the data.

Merge datasets to enhance the analysis.

Visualize key insights using matplotlib and seaborn.


## Tools & Technologies
Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook / Colab

## Dataset
Source: IBM HR Analytics Employee Attrition & Performance

Format: CSV

Rows: ~1470

Columns: 30+ attributes including:

Age, Gender, Job Role, Job Satisfaction

Monthly Income, Years at Company, Work-Life Balance

Attrition (Yes/No), Overtime, etc.


## Data Cleaning & Preprocessing
Covered:

isnull(), notnull(), dropna(), fillna()

Changing data types with astype()

Renaming columns using rename() or columns = []

Removing duplicate entries via drop_duplicates()


## Data Analysis Techniques
  Indexing & Selection
.loc[], .iloc[], .query(), condition-based filtering

GroupBy & Aggregations
Mean satisfaction per department, avg. income vs. attrition, etc.

Merging
If using additional datasets (e.g., manager ratings or department scores), used merge() and concat() to enrich insights.

## Insights
Employees with low job satisfaction and high overtime are more likely to leave.

Work-Life Balance and Years at Company are strong indicators of retention.

Job Role and Monthly Income show significant variance in attrition trends.
