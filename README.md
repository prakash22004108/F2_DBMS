# F2_DBMS
## Date:
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

create table student(rollno int primary key, name varchar(20),age int,address varchar(100),phno varchar(10));

### OUTPUT:
![Screenshot 2023-09-14 092941](https://github.com/Yamunaasri/F2_DBMS/assets/115707860/9a80a4f3-376a-4e99-b402-6e5eaca4cad6)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 

alter table student add dept varchar(10);
### OUTPUT:

![Screenshot 2023-09-14 093422](https://github.com/Yamunaasri/F2_DBMS/assets/115707860/a5dfed70-a471-4049-8c1e-7a7aa1641c07)

### 3) Drop the student table
### SQL QUERY: 
drop table student;
### OUTPUT:
![image](https://github.com/SivaChandranR07/F2_DBMS/assets/113497395/75f5a6fd-a6b7-433f-92de-3d0db4539e12)

### 4) Delete the student table using truncate keyword
### SQL QUERY: 
truncate table student;
### OUTPUT:
![image](https://github.com/SivaChandranR07/F2_DBMS/assets/113497395/9f1ce1de-596e-4bca-a705-d45dd6930053)

### 5) Rename the student table to mystudent
### SQL QUERY:
alter table student
rename to mystudent;
### OUTPUT:
![image](https://github.com/SivaChandranR07/F2_DBMS/assets/113497395/f019247a-0d2b-463e-92da-e21bd01ae00a)

### RESULT:
The Student database has been created and DDL queries using SQL has been executed successfully.
