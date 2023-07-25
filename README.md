# SQL and Tableau Integration for Business Insights

## Overview
Case study provided and developed during the "SQL - MySQL for Data Analytics and Business Intelligence" course by Udemy. The aim of the project is to answer 4 business questions related to employee demographics, management and salary comparison, through working on a comprehensive database which can be found in the "employees_mod.sql" file (under the "employees_mod.zip" folder), along with its relational schema in the "employees_mod_db.pdf" file. The project combines the power of SQL queries to extract relevant data and Tableau to visualize the results in an intuitive and informative dashboard. The whole course can be found here: https://www.udemy.com/course/sql-mysql-for-data-analytics-and-business-intelligence/

## Business Questions
1. Employee Gender Breakdown Each Year

   To provide a detailed breakdown of the gender distribution among employees over the years, I created a bar chart displaying the number of male and female           employees working in the company each year, starting from 1990. The original business question along with the relevant SQL solution can be accessed through         the "Task1.sql" file.
   
2. Comparison of Male and Female Managers from Different Departments

   To analyze the representation of male and female managers across various departments, I created an area chart displaying the number of male to female managers      for each year, starting from 1990, with an added filter allowing you to view the comparison per department. The original business question along with the           relevant SQL solution can be accessed through the "Task2.sql" file.

3. Comparison of Male and Female Managers' Average Salary from Different Departments

   To compare the average salary between female and male employees in the entire company, I created a line chart displaying the differences between the two genders    for each year until 2002, with an added filter allowing you to view the comparison per department. The original business question along with the relevant SQL       solution can be accessed through the "Task3.sql" file.

4. Visualizing Average Salary per Department within a Salary Range

   To obtain the average male and female salary per department within a specified salary range, I created a custom SQL procedure, 'filter_salary', that accepts two    values as input, representing the minimum and maximum salary range, and produces a result-set which is later visualized as a double bar chart. The                  original business question along with the relevant SQL solution can be accessed through the "Task4.sql" file.

## Tableau Dashboard
Each of the SQL queries above resulted in datasets ("Task1.csv", "Task2.csv", "Task3.csv" and "Task4.csv" files respectively) that were saved and later imported into Tableau to create a final dashboard comprising 4 different charts. Each chart provides valuable insights and answers the corresponding business question in a visually appealing manner. 

Feel free to explore the interactive Tableau dashboard through the "SQLandTableau.twbx" file or through the link in the description, to gain a deeper understanding of the employee insights obtained through the integration of SQL and Tableau.
