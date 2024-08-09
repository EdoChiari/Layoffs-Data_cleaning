# SQL-layoffs-data_cleaning

When dealing with a dataset related to work layoffs, it’s crucial to maintain data integrity and ensure that the information is clean and ready for analysis. This SQL script is designed to prepare the dataset by performing several essential data cleaning tasks:

	1.	Removing Duplicates:
	•	Duplicate records can lead to inaccurate analyses, such as overestimating the number of layoffs. The script identifies and removes any duplicate rows to ensure that each record in the dataset is unique.
	2.	Standardizing Data:
	•	Inconsistent formatting (e.g., varying date formats, inconsistent case in text fields) can create confusion and errors in subsequent analyses. This step standardizes key fields to ensure uniformity, making the data more reliable and easier to query.
	3.	Handling Null or Blank Values:
	•	Null or blank values can disrupt analysis and lead to misleading results. The script identifies fields with null or blank values and either fills them with appropriate default values or flags them for further review.
	4.	Removing Unnecessary Columns and Rows:
	•	Not all data in the dataset may be relevant to the analysis of work layoffs. The script removes columns that don’t contribute to the analysis and rows that are irrelevant or incomplete, resulting in a streamlined and more focused dataset.

This code provides a robust foundation for further exploration and analysis of the layoffs dataset, ensuring that the data is clean, consistent, and ready for any subsequent operations.
