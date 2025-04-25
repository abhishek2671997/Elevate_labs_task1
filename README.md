# Elevate_labs_task1
Link : - For codes:- https://colab.research.google.com/drive/1UkAcUU7gfR7PculaPPhU4jOuxfFYXQLD#scrollTo=iU0szlKtBu0m

Data Analyst Task 1 – Data Cleaning & Preprocessing (Netflix Dataset)
🚀 Project Overview
This project is part of the Data Analyst Internship Program where the goal was to perform Data Cleaning and Preprocessing on a raw dataset.
The task involved handling missing values, removing duplicates, fixing inconsistent formats, and preparing the data for further analysis.

🛠 Tools Used
Python (Pandas)

Jupyter Notebook / VS Code

Netflix Titles Dataset (netflix_titles.csv)

🧼 Data Cleaning Steps
Handled Missing Values:

Identified columns with missing data using .isnull().

Imputed or removed missing values based on context.

Removed Duplicates:

Detected and dropped duplicate rows using .drop_duplicates().

Standardized Text Values:

Standardized inconsistent values in country, rating, and other text columns.

Formatted Dates:

Converted date_added to uniform datetime format (dd-mm-yyyy).

Renamed Columns:

Cleaned column names by making them lowercase and replacing spaces with underscores.

Corrected Data Types:

Ensured release_year is int, and date_added is datetime.

📚 Project Learnings
Gained hands-on experience with real-world messy data.

Learned techniques for missing value treatment, duplicate removal, and standardization.

Understood the importance of consistent data types for reliable analysis.

📁 Files Included
netflix_titles.csv – Original dataset.

cleaned_dataset.csv – Final cleaned dataset.

Screenshots (submission confirmations).

task 1.pdf – Problem statement and guidelines.

📋 How to View
Open cleaned_dataset.csv in any spreadsheet tool (Excel/Google Sheets) or using Pandas.

Compare it with netflix_titles.csv to observe the cleaning improvements.

📢 Special Notes
Only free tools were used (Python + Pandas).

Focused heavily on maintaining data quality and consistency throughout the cleaning process.

