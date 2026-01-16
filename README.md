# 150125_srvb14-Excel-Data-Cleaning-Project
Data Cleaning &amp; Preparation using Microsoft Excel

📊 Project Overview

This project demonstrates a complete data cleaning workflow using spreadsheet tools like Microsoft Excel, simulating how a data analyst prepares raw data for analysis.
The focus is on handling messy datasets containing missing values, duplicates, inconsistent formats, and unstandardized text fields. The final output is a clean, analysis-ready dataset exported in both Excel and CSV formats.

🛠 Tools Used
Primary Tools : Microsoft Excel

📁 Dataset Information
The project can be performed using any of the following datasets:
Netflix Movies and TV Shows Dataset (Kaggle)

🔍 Data Cleaning Steps
1️⃣ Dataset Import
Downloaded dataset in CSV format from Kaggle
Ensured correct delimiter separation
Verified first row as column headers

2️⃣ Dataset Exploration
Used Freeze Panes to lock header rows
Applied filters to all columns for quick exploration

3️⃣ Handling Missing Values
Identified blank values using Filters → Blanks
Highlighted missing cells using Conditional Formatting
Decisions made per column:
Replace (when logical)
Remove rows
Leave blanks if meaningful

4️⃣ Duplicate Detection
Used Remove Duplicates feature
Key columns used (e.g., ID, Title)
Created a backup sheet before deletion

5️⃣ Text Standardization
Applied Excel functions:
TRIM() – remove extra spaces
PROPER() – standardize names
UPPER() – normalize categorical values

6️⃣ Data Type Validation
Standardized date formats (YYYY-MM-DD)
Removed symbols from numeric columns
Corrected spelling variations in categorical data

7️⃣ Cleaned Dataset Creation
Created a new sheet: Cleaned_Data
Copied only the final cleaned output
Maintained separation between raw and processed data

8️⃣ Data Quality Notes
Added column: Data_Quality_Notes
Demonstrates analyst reasoning and documentation

9️⃣ Final Output
Saved file as Cleaned_dataset.xlsx
Exported cleaned_dataset.csv for further analysis
