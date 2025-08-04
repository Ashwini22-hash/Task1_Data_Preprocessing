Data Cleaning and Preprocessing - README
 Objective : This Task demonstrates essential steps for cleaning and preprocessing raw data using Python and pandas. The dataset used is Customer Personality Analysis.

 Dataset
•	Source: Local CSV file: Customer_Personality_Analysis.csv
•	Used Library: pandas

 Steps Performed
1.	Loading Data:
•	Loaded CSV data using pandas.read_csv().
2.	Initial Exploration:
•	Displayed first few rows with .head()
•	Checked dataset shape using .shape
3.	Missing Values:
•	Checked for null values with .isnull()
4.	Duplicates:
•	Removed duplicate rows using .drop_duplicates()
5.	Standardizing Text:
•	Converted Marital_Status and Education columns to lowercase for consistency
6.	Date Format Conversion:
•	Converted Dt_Customer to datetime format with dayfirst=True
7.	Column Name Cleanup:
•	Renamed all column headers to lowercase with underscores (e.g., Marital_Status → marital_status)
8.	Data Type Conversion:
•	Converted the income column to float type
9.	Exporting Cleaned Data:
•	Saved the cleaned data to a new CSV file
