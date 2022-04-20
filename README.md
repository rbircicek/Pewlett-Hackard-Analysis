# Pewlett-Hackard-Analysis

#The Project Summary

Now that Bobby has proven his SQL chops, his manager has given both of you two more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

# Outcome

This project consists of two technical analysis deliverables and a written report.

Deliverable 1: The Number of Retiring Employees by Title

Deliverable 2: The Employees Eligible for the Mentorship Program

Deliverable 3: A written report on the employee database analysis (README.md)

# Resources

Data Source: Employee_Database_challenge.sql

Software: pgAdmin 4.26, Python 3.8.3

# Important Keys to know

Database Keys: Database keys identify records from tables and establish relationships between tables. There are many types of keys. For this project, the  focus will be on  primary keys and foreign keys.

Primary Keys: The departments.csv file has a dept_no column with unique identifiers for each row (one department number per department). For example, d001 will always reference the Marketing Department, across other worksheets. This unique identifier is known as a primary key. Primary keys are an important part of database design. When a database is being created, each table added must include a primary key in the architecture. Primary keys serve as a link between these tables.

Foreign Keys: Foreign keys are just as important as primary keys. While primary keys contain unique identifiers for their dataset, a foreign key references another dataset's primary key. This is like a phone number. You have your own phone number. It's your number, assigned to your phone, and unique to you. Even other carriers cannot assign this number to their customers. This is your primary key. Your friends and family members also have a primary key: their own phone number.
When you save their numbers in your phone, you're creating a reference to these people, also known as foreign keys. Your phone has lots of foreign keys (such as doctors offices, friends, and other family members), but only one primary key.

# Entity Relationship Diagrams (ERD)
An entity relationship diagram (ERD) is a type of flowchart that highlights different tables and their relationships to each other. The ERD does not include any actual data, but it does capture the following pertinent information from each CSV file:

Primary keys
Foreign keys
Data types for each column

The ERD for this project is in the PNG folder. 

# Deliverable 1: The Number of Retiring Employees by Title
Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a Retirement Titles table that holds all the titles of current employees who were born between January 1, 1952 and December 31, 1955. Because some employees may have multiple titles in the database—for example, due to promotions—you’ll need to use the DISTINCT ON statement to create a table that contains the most recent title of each employee. Then, use the COUNT() function to create a final table that has the number of retirement-age employees by most recent job title.

A query is written and executed to create a Retirement Titles table for employees who are born between January 1, 1952 and December 31, 1955
The Retirement Titles table is exported as retirement_titles.csv

A query is written and executed to create a Retiring Titles table that contains the number of titles filled by employees who are retiring.
The Retiring Titles table is exported as retiring_titles.csv

Please see the PNG and CSV Folders.

# Deliverable 2: The Employees Eligible for the Mentorship Program

Deliverable Requirements:

Using the ERD you created in this module as a reference and your knowledge of SQL queries, create a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.

A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.
The Mentorship Eligibility table is exported and saved as mentorship_eligibilty.csv

A query is written and executed to create a Mentorship Eligibility table for current employees who were born between January 1, 1965 and December 31, 1965.

# Analysis

There is a large number of staff members that are eligible for retirement. The breakdown by the job title is given below.  

![Retiring Titles](https://user-images.githubusercontent.com/96134924/164143509-3d25922d-15f8-42c6-b9b7-de44c59094ae.png)










