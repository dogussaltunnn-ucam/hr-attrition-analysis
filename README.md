# HR Employee Attrition Analysis

This project analyzes employee attrition patterns using SQL in DBeaver and Tableau.

## Tools Used
- SQL
- DBeaver
- Tableau Public

## Project Workflow
1. Imported the HR dataset into DBeaver
2. Cleaned and structured the data with SQL
3. Created summary queries to identify attrition patterns across employee groups
4. Exported SQL outputs as CSV files
5. Built a Tableau dashboard to present key attrition drivers visually

## Files
- `hr_attrition_clean.csv`: cleaned HR dataset used for analysis
- `hr_queries.sql`: SQL queries used for cleaning and analysis
- dashboard image: final Tableau dashboard screenshot

## Analysis Focus
- overall attrition rate
- attrition rate by overtime
- attrition rate by department
- attrition rate by job role
- attrition rate by business travel
- attrition rate by tenure bucket
- average monthly income by attrition status

## Key Insights
- Employees working overtime show a much higher attrition rate than those who do not.
- Sales has the highest attrition rate among departments.
- Sales Representative is the highest-risk job role in the dataset.
- Employees with shorter tenure, especially 0 to 2 years, are more likely to leave.
- Frequent business travel is associated with higher attrition.
- Employees who leave tend to have lower average monthly income than those who stay.

## Dashboard Focus
The dashboard highlights:
- attrition differences between overtime and non-overtime employees
- attrition trends across departments and job roles
- travel-related attrition patterns
- tenure-based attrition risk
- income differences between employees who stay and leave

## Outcome
This project demonstrates how SQL and Tableau can be used together to transform HR data into clear business insights and build a portfolio-ready dashboard focused on employee retention.
