README.md

 Titanic Data Cleaning and Preprocessing using Python
  Project Overview

This project demonstrates the complete data cleaning and preprocessing workflow using the Titanic dataset. The goal is to transform raw data into a clean, structured, and analysis-ready format by addressing common data quality issues such as missing values, duplicate records, inconsistent formats, and categorical variables.

The cleaned dataset can be used for exploratory data analysis (EDA) or as a foundation for machine learning models.

Objectives
Load and inspect the dataset
Handle missing values
Remove duplicate records
Standardize column names
Clean text data
Encode categorical variables
Detect and analyze outliers
Validate data quality
Save the cleaned dataset for future analysis
📂 Dataset Information

The dataset contains passenger information from the Titanic disaster, including:

Passenger ID
Survival Status
Passenger Class
Name
Gender
Age
Number of Siblings/Spouses
Number of Parents/Children
Ticket Number
Fare
Cabin
Port of Embarkation
🛠️ Data Cleaning & Preprocessing Steps

✔ Loaded and explored the dataset

✔ Inspected data types and descriptive statistics

✔ Checked for missing values

✔ Filled missing values in the Age column using the median

✔ Filled missing values in the Embarked column using the mode

✔ Removed the Cabin column due to a high percentage of missing values

✔ Checked for duplicate records

✔ Standardized column names

✔ Trimmed and standardized text values

✔ Encoded the Sex column into a binary feature (is_female)

✔ Applied one-hot encoding to the Embarked column

✔ Detected outliers using box plots and the IQR method

✔ Performed data validation checks

✔ Saved the cleaned dataset

📊 Exploratory Data Analysis

The notebook also includes:

Survival Distribution
Passenger Class Distribution
Gender Distribution
Age Distribution
Fare Distribution
Correlation Heatmap
💻 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
