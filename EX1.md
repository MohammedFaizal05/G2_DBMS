# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 

create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);

### OUTPUT:

![image](https://github.com/MohammedFaizal05/G2_DBMS/assets/120553195/36c69d10-5867-4706-a956-192d10ba0794)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department char(30);
### OUTPUT:

![image](https://github.com/MohammedFaizal05/G2_DBMS/assets/120553195/c192e8d8-58ea-43eb-bf5c-31fbb5d4f68a)

### 3) Drop the student table
 
### SQL QUERY: 
drop table student;

### OUTPUT:
![image](https://github.com/MohammedFaizal05/G2_DBMS/assets/120553195/1099395f-0bf9-4911-9493-ffb81f430e75)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:

![image](https://github.com/MohammedFaizal05/G2_DBMS/assets/120553195/870162d3-c5ab-4e0e-8965-b008a6e3ec90)


### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student rename to mystudent;

### OUTPUT:
![image](https://github.com/MohammedFaizal05/G2_DBMS/assets/120553195/c1ce061d-7f16-467d-a310-d6e1162526a8)
