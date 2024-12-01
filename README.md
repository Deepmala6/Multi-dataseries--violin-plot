# Multi-dataseries--violin-plot

*---Salary Analysis with Violin Plots---*

*---Project Description---*

This project is focused on visualizing salary distributions across different employee attributes using violin plots. The plots aim to uncover patterns and insights into salary trends based on factors such as experience, job title, company location, and more. These visualizations are particularly helpful for HR analytics, workforce planning, and data-driven decision-making.

*---Dataset Details---*
The dataset used in this project represents a collection of employee salary records with the following key attributes:

Dataset Columns:

1. experience_level:
Indicates the level of experience of the employee.
Categories: Entry-level, Mid-level, Senior-level, and Expert-level.
Example values: EN, MI, SE, EX.

2. employment_type:
Represents the type of employment.
Categories: Full-time, Part-time, Contractual, Freelance.
Example values: FT, PT, CT, FL.

3. salary_in_usd:
The annual salary of the employee, expressed in USD.
Numeric values.


4. company_size:
Describes the size of the company where the employee works.
Categories: Small, Medium, Large.
Example values: S, M, L.

5. job_title:
The role or designation of the employee within the company.
Examples: Data Scientist, Software Engineer, Project Manager.

6. company_location:
The country where the company is located.
Example values: US, UK, IN, DE.

7. work_year:
The year in which the salary data was recorded.
Example values: 2020, 2021, 2022.


*---Visualizations---*

1. 1x3 Grid of Violin Plots
Three violin plots are displayed in a single row:

Plot 1: Experience Level vs Salary:
Purpose: Shows how salaries vary across different experience levels.
Insight: Helps identify whether seniority significantly impacts salaries.

Plot 2: Employment Type vs Salary:
Purpose: Visualizes salary distributions based on the type of employment.
Insight: Highlights differences in salaries between full-time, part-time, and other types of employment.

Plot 3: Company Size vs Salary:
Purpose: Analyzes the impact of company size on salary.
Insight: Reveals trends such as whether larger companies tend to offer higher salaries.


2. Job Title vs Salary
Description: A standalone violin plot depicting salary distributions across various job titles.

Features:
Provides insights into how salaries differ among job roles.
The x-axis labels are rotated for readability due to the large number of job titles.

3. 1x2 Grid of Violin Plots
Two violin plots are displayed side by side:

Plot 1: Company Location vs Salary:
Purpose: Shows salary variations by company location.
Insight: Highlights geographic salary trends and differences.

Plot 2: Work Year vs Salary:
Purpose: Analyzes salary distributions across different years.
Insight: Reveals whether salaries have grown or stagnated over time.
 
 *---Key Features of Violin Plots---*
Combines the features of box plots (median, quartiles) and kernel density estimation.
Provides a visual representation of data distribution and density.
Enables comparisons between categories within a variable.

*---Prerequisites---*

1. Libraries Required:
Matplotlib: For rendering plots.
Seaborn: For creating violin plots with aesthetic styling.
Pandas: For handling and preprocessing the dataset.

2. Python Version:
The code is compatible with Python 3.7 or higher.


*---How to Use This Script---*

1. Prepare the Dataset:
Ensure your dataset is loaded into a Pandas DataFrame named df.
Verify that the column names in your dataset match the ones used in the script.


2. Run the Script:
Use a Python environment with visualization support (e.g., Jupyter Notebook, PyCharm, VS Code with a Jupyter plugin).
Copy and paste the code into a Python script or notebook.

*---View the Visualizations:---*
The violin plots will render inline (e.g., in Jupyter) or in a pop-up window, depending on your setup.


1. File Explanation
Code File:

The script includes:
1x3 Violin Plot Grid:
Focused on experience_level, employment_type, and company_size vs salary_in_usd.
Single Job Title vs Salary Plot:
Highlights the salary trends across job roles.

1x2 Violin Plot Grid:
Analyzes the impact of company_location and work_year on salary_in_usd.

Output:
The script generates multiple plots, offering detailed insights into the relationship between salary and various factors.
