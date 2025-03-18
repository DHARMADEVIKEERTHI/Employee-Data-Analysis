# Employee Data Cleaning & Analysis Project

## 📖 Project Overview
This project focuses on cleaning, preprocessing, and analyzing an employee dataset using Python and Pandas. The dataset contains employee information such as salary, performance scores, job titles, and more.

## 🛠 Key Tasks Performed
1. Missing Salary Imputation

Imputed missing salary values using the median salary per department.
2. Duplicate Employee ID Check

Identified duplicate employee IDs and printed them.
3. Performance Score Conversion

Converted performance_score to an integer and replaced None or invalid values with -1.
4. Date Format Standardization

Converted join_date to YYYY-MM-DD format.
Extracted join_year from the join_date.
5. Department Typo Correction

Corrected typos in the department column.
6. Salary Outlier Removal

Removed salaries more than 3 standard deviations from the mean.
7. Email Domain Extraction

Extracted the domain part of the email into a new column email_domain.
8. Pearson Correlation Calculation

Calculated the correlation between salary and join_year.
9. Average Salary Aggregation (Pivot Table)

Created a pivot table showing average salary by department and job_level.
10. Duplicate Row Removal

Removed complete duplicate rows and verified the cleanup.
11. Null Value Handling

Replaced missing names with 'Unknown'.
Filled missing emails with 'unknown@example.com'.
12. Job Level Assignment

Created a job_level column based on job_title (e.g., Junior, Mid, Senior, Manager).
## 📊 Tools & Technologies Used
Python 3
Pandas Library
NumPy
Jupyter Notebook
# 📁 How to Run
Clone this repository or download the code files.
Place the empd.csv dataset in the project directory.
Install necessary libraries (if not installed):
bash
Copy
Edit
pip install pandas numpy
Run the Python script or notebook:
bash
Copy
Edit
python employee_analysis.py
or open the .ipynb file in Jupyter/Colab.
# 📌 Output Highlights
Cleaned dataset with no duplicates or nulls in critical columns.
email_domain, join_year, and job_level columns added.
Correlation printed for salary vs. join year.
Pivot table for salary aggregation.
All handling for missing data, type conversion, and outlier removal completed.
# ✅ Example Columns After Cleaning
employee_id	first_name	last_name	email	email_domain	department	job_title	salary	join_date	performance_score	join_year	job_level
1001	John	Doe	john.doe@gmail.com	gmail.com	Sales	Senior Manager	75000	2020-05-10	8	2020	Manager
1002	Unknown	Unknown	unknown@example.com	example.com	IT	Junior Developer	55000	2019-03-15
