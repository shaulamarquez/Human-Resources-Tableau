# Human Resources Dashboard

![image](https://github.com/user-attachments/assets/e1f2a0a9-0aba-4ada-b142-a1aeaea85214)
![image](https://github.com/user-attachments/assets/b4dbd54d-16a3-4447-8121-f66ac7638135)

[Human Resources Dashboard](https://public.tableau.com/app/profile/shaula.marquez/viz/HRDashboardportfolio/HRSummary?publish=yes)

# Introduction 

This is a comprehensive dashboard to analyze human resources data, providing summary views for high level insights and detailed employee records for in-depth analysis.

# Overview
The Overview section should provide a snapshot of the overall HR metrics, including:

* Display the total number of hired employees, active employees, and terminated employees.
* Visualize the total number of hired and terminated employees over the years.
* Present a breakdown of total employees by department and job titles.
* Compare total employees between headquarters (HQ) and branches (New York is the HQ)
* Show the distribution of employees by city and state.

# Demographics
The Demographics section should offer insights into the composition of the workforce, including:

* Present the gender ratio in the company.
* Visualize the distribution of employees across age groups and education levels.
* Show the total number of employees within each age group.
* Show the total number of employees within each education level.
* Present the correlation between employees’s educational backgrounds and their performance ratings.

# Income
The income analysis section should focus on salary-related metrics, including:

* Compare salaries across different education levels for both genders to identify any discrepancies or patterns.
* Present how the age correlate with the salary for employees in each department.

# Employee Records View

* Provide a comprehensive list of all employees with necessary information such as name, department, position, gender, age, education, and salary.
* Users should be able to filter the list based on any of the available columns.

# The dataset has the following attributes (ChatGPT Generated):
* Employee ID: A unique identifier.
* First Name: Randomly generated.
* Last Name: Randomly generated.
* Gender: Randomly chosen with a 46% probability for ‘Female’ and a 54% probability for ‘Male’.
* State and City: Randomly assigned from a predefined list of states and their cities.
* Hire Date: Randomly generated with custom probabilities for each year from 2015 to 2024.
* Department: Randomly chosen from a list of departments with specified probabilities.
* Job Title: Randomly selected based on the department, with specific probabilities for each job title within the department.
* Education Level: Determined based on the job title, chosen from a predefined mapping of job titles to education levels.
* Performance Rating: Randomly selected from ‘Excellent’, ‘Good’, ‘Satisfactory’, ‘Needs Improvement’ with specified probabilities.
* Overtime: Randomly chosen with a 30% probability for ‘Yes’ and a 70% probability for ‘No’.
* Salary: Generated based on the department and job title, within specific ranges.
* Birth Date: Generated based on age group distribution and job title requirements, ensuring consistency with the hire date.
* Termination Date: Assigned to a subset of employees (11.2% of the total) with specific probabilities for each year from 2015 to 2024, ensuring the termination date is at least 6 months after the hire date.
* Adjusted Salary: Calculated based on gender, education level, and age, applying specific multipliers and increments.
* Be sure to structure the code cleanly, using functions where appropriate, and include comments to explain each step of the process.

