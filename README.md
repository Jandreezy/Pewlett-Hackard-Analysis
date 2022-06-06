# Pewlett Hackard Analysis
Performing analysis of company employee data by utilizing the dynamic ability of the relational database PostgresSQL to transform and query data.

##  Resources 
- Python, JupyterLab, PostgreSQL, Pgadmin

## Overview 
The purpose of this project is to perform analysis on a large-scale of employee data for a company with over 300,000 employees.
The company Pewlett Hackard is reviewing staffing metrics, namely retirement and needs assistance going through the data to see who is close or elligible for retirement.

## Results 
### Deliverable 1: The Number of Retiring Employees by Title
- A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955
- The Retirement Titles table is exported as retirement_titles.csv
- A query is written and executed to create a Unique Titles table that contains the employee number, first and last name, and most recent title.
- The Unique Titles table is exported as unique_titles.csv
- A query is written and executed to create a Retiring Titles table that contains the number of titles filled by employees who are retiring.
- The Retiring Titles table is exported as retiring_titles.csv

![1](https://github.com/Jandreezy/Pewlett-Hackard-Analysis/blob/main/Resources/Eligible%20for%20retirement.png?raw=true)

### Deliverable 2: The Employees Eligible for the Mentorship Program
- A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.
- The Mentorship Eligibility table is exported and saved as mentorship_eligibilty.csv
- Only 1549 total employees qualify for mentorship/training for an internal promotion

![2](https://github.com/Jandreezy/Pewlett-Hackard-Analysis/blob/main/Resources/Eligible%20for%20mentorship.png?raw=true)

## Summary 
- The departments with the highest number of potential retirees are Development(25.45%),Production(22.30%) and Sales(7.27%)

![3](https://github.com/Jandreezy/Pewlett-Hackard-Analysis/blob/main/Resources/Depts%20and%20retirees.png?raw=true)

- Based on my analysis, Pewlett Hackard is potentially facing over 90,000 vacant positions. A suggestion would be to increase the amount of employees into the mentorship program because the total number of employees that qualify are 60x less than the amount of employees that could potentially be retiring.


