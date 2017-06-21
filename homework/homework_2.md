## CSCI 3308 Software Development Methods and Tools [Summer 2017]

**Instructor:** Chris Womack | **Homework #2** – Material by Liz Boese | **Due Date:** 23:55 on Jun 19

### Objectives:
- Write SQL statements
- No pair programming on this Homework.

**Assignment**
Download the file for HW2 (HW2-populate.sql from Moodle) and submit a .sql file answering the following questions.

**Database Setup**
1. Go to the directory where you downloaded the HW2-populate.sql file.
2. Log in to mysql (Hint: you need to first start your mysql instance)
3. Create a database and run the downloaded SQL script.

**Commands:**
```SQL
     show databases;
     create database HW2;
     show databases;
     use HW2;
     show tables;
     source HW2-populate.sql
     show tables;
```
**Questions**
Create a text file named **Firstname_Lastname_HW2.sql** with your SQL statement answers for the following as a working .sql file. Test your script with the command: ```source Firstname_Lastname_HW2.sql```
1. List all state names and their 2-letter codes.
2. Write a query to report the following information for all counties whose names start with "Prince". (Hint: Use "*like*").
Expected Output columns:
   `a. name`
   `b. statecode`
   `c. populate_1950`
   `d. population_2010`

3. Write a single query to list only the population in year 2010 for the state represented by Sen. Richard Lugar. Output column: `populate_2010`

4. Write a single query to report only the total number of the counties in 'Maryland'. The query should not hard-code the state code for Maryland (join the two tables in the ```WHERE``` clause)

5. Write a single query to find the name of the state that was admitted last into the union. Hint: Use nested subquery.

6. Find all democratic (i.e., with affiliation = 'D') senators that are not chairman of any committee or subcommittee. Expected Output columns: ```name``` Order by name.

**Credit:**
To receive credit for this assignment: Submit a SQL file named **Firstname_Lastname_HW2.sql on moodle.**
