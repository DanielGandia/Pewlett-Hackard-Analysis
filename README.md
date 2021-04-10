# Pewlett-Hackard-Analysis

## Overview of the Analysis
Determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.
## Resources
- Data Sources: ratings.csv, city_data.csv
- Software: PostgreSQL, pgAdmin, Visual Studio Code 1.54

## Results
The results of the SQL query for the first deliverable show that the "silver tsunami" has a total of 90,398 employees retiring. 

The below table shows:
- 7 titles of the retiring employees. 
- Number of employees that will be retiring. 

Retiring Titles | Number of Employees
------------ | -------------
Senior Engineer  | 29,414 
Senior Staff  | 28,254
Engineer  | 14,222
Staff  | 12,243
Technique Leader  | 4,502
Assistant Engineer  | 1,761
Manager  | 2

As part of the second deliverable, the SQL query shows that there are 1,539 employees eligible for the mentorship program. 

The below table shows:

- The number of employees eligible for the mentorship program.
- 6 titles for the mentorship program.

Mentorship Titles | Number of Employees
------------ | -------------
Senior Staff  | 569
Senior Engineer  | 501
Engineer  | 169
Staff  | 155
Technique Leader  | 78
Assistant Engineer  | 77

## Summary

How many roles will need to be filled as the "silver tsunami" begins to make an impact? 

- The number roles that will need to be filled in the first year of the "silver tsunami" is 31,374. 

Please see the below image with the both queries and result of the count of employees:

![summary_response.png](https://github.com/DanielGandia/Pewlett-Hackard-Analysis/blob/main/Resources/summary_response.png)

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

- There seem to be enough employees in the mentorship program to cover each position, except for the "Manager" position. Also, there are not enough employees 

![mentorship_titles.png](https://github.com/DanielGandia/Pewlett-Hackard-Analysis/blob/main/Resources/mentoship_titles.png)