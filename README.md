# Pewlett-Hackard-Analysis
## Overview of Project
In this challenge, we are applying what we've done earlier in the modules and creating a new assignment that consists of two technical analysis deliverables.
The assignment is to help "Bobby's" manager to determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program. 

### Resources: 
##### PostgreSQL13, PgAdmin v4, .csv files supplied

### Objective:
###### Deliverable 1: The Number of Retiring Employees by Title

###### Deliverable 2: The Employees Eligible for the Mentorship Program

## Results: 
###### Deliverable 1: Because some employees may have had mulitple titles in the database it needed to be sorted out and made presentable with a table that had the number of retirement-age employees by most recent job title. Below is an image of the finished table.
![image](https://github.com/antxamp/Pewlett-Hackard-Analysis/blob/main/Deliverable%20png%20folder/deliverable_1.png)

###### Deliverable 1a. The next table is filtering out with unique titles.
![image](https://github.com/antxamp/Pewlett-Hackard-Analysis/blob/main/Deliverable%20png%20folder/deliverable_2.png)

###### Deliverable 1b. The last table for indicates the number of of titles from the unique titles table.

![image](https://github.com/antxamp/Pewlett-Hackard-Analysis/blob/main/Deliverable%20png%20folder/deliverable_2b.png)

###### Deliverable 2: Creating a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.

![image](https://github.com/antxamp/Pewlett-Hackard-Analysis/blob/main/Deliverable%20png%20folder/deliverable_2mentorship.png)

### Summary to Manager:
##### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
######  According to the tables created here is the list of retired employees with their unique titles that will be retiring within the company. With the amount of employees currenlty at 499,986 according to the employees id list. The retirement percentage is at 18%. 
![image](https://github.com/antxamp/Pewlett-Hackard-Analysis/blob/main/Deliverable%20png%20folder/deliverable_2b.png)

##### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
######  According to the chart below. After coming up with a figure of 1940 mentors available to mentor the next generation. Management would have to come up with a different plan and not to have a 1-on-1 mentorship for upcoming employees to be mentored. The amount of mentors is too low for 1-on-1 mentorships but there is enough that are qualified. 
##### ![image](https://github.com/antxamp/Pewlett-Hackard-Analysis/blob/main/Deliverable%20png%20folder/mentorship_summary.png)

