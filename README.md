# SQL-Master
| SR_Nbr | Assignment Name  | Exercises |
| --------------- | --------------- | --------------- |
| 1 | Database and Table Creation <br /> DDL Commands (Data Definition Language) |  |
| 2 | Constraints |  |
| 3 | DML Commands <br /> (Data Manipulation Language) |  |
| 4 | Querying Database |  |
| 5 | Nested Queries and other Operations |  |
| 6 | Views |  |


##	PROJECT-EMPLOYEE DATABASE :
        This database maintains the details of employees and the projects.  
                                 Consider the following database:

       PROJECT (PNO INTEGER pk, PNAME VARCHAR (30), PTYPE VARCHAR 
     (20), DURATION INTEGER)

       EMPLOYEE (ENO INTEGER pk ,ENAME VARCHAR(20) not null,	QUALIFICATION 
                                           VARCHAR(15), SALARY FLOAT, JOINING_DATE DATE)

       Project_EMP(pno int FK,eno int FK, START_DATE, NO_OF_HOURS_WORKED)
  Relationship between PROJECT and EMPLOYEE is MANY to MANY with descriptive attribute START_DATE, NO_OF_HOURS_WORKED.


Exercise 1: Database and Table Creation - USE DDL Commands (Data Definition Language)
	To create database
	To create simple tables with only the primary key constraint as a table level constraint & as a field level constraint) (include all data types)

	GETTING STARTED
	You can connect to SQL server, Now use Microsoft SQL Server Management Studio and create respective databases and tables as described above:

A)	Project-Employee
1.	Create following tables with proper primary key constraint (Underlined Attribute) and Foreign Key constraints.
PROJECT (PNO INTEGER, PNAME VARCHAR (30), PTYPE VARCHAR (20), DURATION INTEGER);
EMPLOYEE (ENO INTEGER, ENAME VARCHAR(20), QUALIFICATION  VARCHAR(15), SALARY FLOAT, JOINING_DATE DATE)
2.	Add the column STATUS to Project table.
3.	Add column contact_number to employee table.
4.	Add Age column to employee table.
5.	Add Budget column to project table.
6.	Drop table employee.
