# Pewlett-Hackard-Analysis

## Overview of the analysis: 
In this analysis I have determined the number of retiring employees by titles and identified any retiring employees that are eligible for the mentorship program. 

## Results:

1. Senior engineers and staff makes up a huge number of titles getting ready to retire. This leaves the question of wanting to promote from within or hire people from the outside. 
2. A single employee can have several promotions leading to retirement. We want to make sure that we have the right position retiring because this can lead to discrepancies in staffing. 
3. The unique titles table shows every employee with the current retiring title. Over 40,000 titles in the retirement title table are duplicate employee numbers. 
4. In the retiring titles table, a total of 90398 titles will have a vacant spot but only 1549 employees qualify for the mentorship program.

## Summary:

How many roles will need to be filled as the "silver tsunami" begins to make an impact?
90398 titles will be retiring. Below is the count of all the titles that will be retiring. 

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Each mentor will have a group of about 60 new employees. This will be difficult for the mentors to divide their time between each employee

Since there is not enough retired employees to be a mentor to new employees, I figured we can use current employees as mentors. I used the first query to create a table of employees 
that have not retired. Next, I queried the number of titles by department. Now we can pair a new employee with an experienced PH employee in the right department.  
