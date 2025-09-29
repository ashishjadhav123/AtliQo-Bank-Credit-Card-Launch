# AtliQo-Bank-Credit-Card-Launch


Phase 1: Target Market Identification

This repository documents the complete data analysis workflow followed in Phase 1 of the project. The focus is on understanding the customer base and identifying the target market through data validation, cleaning, visualization, and insights.

Data Validation of Acquired Data
Validated all datasets for structure, completeness, duplicates, formatting issues, and inconsistencies.

Data Understanding and MySQL Setup
Explored each dataset to understand columns, data types, and relationships. Configured the MySQL environment and created the database schema.

Data Import in Jupyter Notebook
Imported data into Jupyter Notebook using Python and Pandas. Established connection with MySQL for data handling.

Data Cleaning: Handling NULL Values (Annual Income)
Identified missing values in the annual_income field and applied suitable imputation techniques.

Data Cleaning: Treating Outliers (Annual Income)
Detected outliers using IQR or Standard Deviation and handled them to maintain data integrity.

Data Visualization: Annual Income
Visualized the annual income distribution using appropriate charts.

Exercise: Treat Outliers in Age Column
Applied outlier detection techniques to the age column.

Solution: Treat Outliers in Age Column
Provided the solution for treating outliers in the age column.

Data Visualization: Age, Gender, Location
Created visualizations to analyze demographic and location-based trends.

Data Cleaning: Credit Score Table (Part 1 and Part 2)
Handled missing data and inconsistencies in the credit score table. Standardized credit score values for consistent analysis.

Correlation Among Credit Profile Variables
Analyzed relationships between credit-related variables using correlation techniques.

Exercise: Handle NULL Values in Transactions Table
Worked on handling missing values in the transactions table.

Solution: Handle NULL Values in Transactions Table
Provided the solution for handling NULL values in the transactions data.

Data Cleaning: Treat Outliers Using IQR (Transaction Amount)
Managed extreme values in the transaction_amount column using IQR.

Data Visualization: Transactions Table
Visualized transaction data before and after cleaning.

Finalizing the Target Group
Identified the target group based on demographics, spending patterns, and credit behavior.

Preparation for Phase 2
Organized cleaned datasets and insights for upcoming analysis in Phase 2.

Repository Structure (Suggested)

data/

notebooks/

visuals/

scripts/

README.md

Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook

Next Step
Proceeding to Phase 2 using the validated, cleaned, and analyzed datasets from Phase 1.