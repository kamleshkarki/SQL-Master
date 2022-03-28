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
        ###This database maintains the details of employees and the projects.  
         #Consider the following database:
        1. PROJECT (PNO INTEGER pk, PNAME VARCHAR (30), PTYPE VARCHAR (20), DURATION INTEGER)
        2. EMPLOYEE (ENO INTEGER pk ,ENAME VARCHAR(20) not null, QUALIFICATION VARCHAR(15), SALARY FLOAT, JOINING_DATE DATE)
        3. Project_EMP(pno int FK,eno int FK, START_DATE, NO_OF_HOURS_WORKED)
        4. Relationship between PROJECT and EMPLOYEE is MANY to MANY with descriptive attribute START_DATE, NO_OF_HOURS_WORKED.
