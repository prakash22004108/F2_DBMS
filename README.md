# F2_DBMS
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
```
create table student(rollno char(5), name varchar(20), age char(5), address varchar(100), phoneno char(15));
```
### OUTPUT:
![1](https://github.com/Ronick2005/F2_DBMS/assets/83219341/6ba921dc-a3e5-4bcf-8e35-d6fc0831922b)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
ALTER TABLE student
ADD department varchar(30);
```
### OUTPUT:
![2](https://github.com/Ronick2005/F2_DBMS/assets/83219341/e62e635f-3c55-4a18-babb-a7bb6e78dcf2)

### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```
### OUTPUT:
![3](https://github.com/Ronick2005/F2_DBMS/assets/83219341/01dbd2bd-e9ab-4d9a-8be9-b8157330924b)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```
### OUTPUT:
![4](https://github.com/Ronick2005/F2_DBMS/assets/83219341/a4b3b48a-f720-4eed-a776-2b47f024ca91)

### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student
rename to mystudent;
```
### OUTPUT:
![5](https://github.com/Ronick2005/F2_DBMS/assets/83219341/e2f4e148-4f54-401b-89c7-4c192eb48a49)

### RESULT:
Hence successfully created a student database and execute DDL queries using SQL.
