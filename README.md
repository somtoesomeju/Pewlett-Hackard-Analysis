# Pewlett-Hackard-Analysis

# Overview
In this analysis, I am using CSV files from a dataset of employees in a company to determine the number of retiring employees by title; and also to determine which of the employees would be eligible for a mentorship program offered by the company.
I am taking advantage of SQL in this analysis, which will allow me to create a new set of CSV files holding the data.

# Resources
- Software: PGAdmin 4 version 5.2, Microsoft Excel for Mac
- Languages used: SQL

# Results
 - From the data, I was able to get the number of employees ready for retirement. This was done by first creating a new table by performing an inner join between employees.csv table and the titles.csv table. The employees table holds all employee names and their employee number, while the titles table holds the employee number and their position in the company (e.g. manager). Merging both tables allowed us to get all of the employees by their names and titles. By filtering their birth dates, I was able to get a dataset that included employees about to retire. This was imported into a new table called "retirement_titles.csv". After deriving the table, I made another table called "unique" that is similar to the previous table, but it eliminates how long they have worked with the company. From that table, I was able to count the employees about to retire by their position in the company[image](https://github.com/somtoesomeju/Pewlett-Hackard-Analysis/blob/main/Data/Screen%20Shot%202021-08-15%20at%201.28.51%20PM.png).The results show that the majority of the employees retiring are the senior engineers. 

- In the second delierable, I created a table holding employees born in the year 1965. This table holds the employees that would be eligible for the mentorship program. The table was created in a similar way as the "retiring_titles.csv" table. The only difference was that the birth year was filtered to just include 1965.

# Conclusion
From the tables created, its clear that almost half of the employees are ready for retirement, and a new strategy has to come in place to accomodate them. Retiring employees also means that a hiring surge has to happen soon to fill up the soon to be vacant slots. 
