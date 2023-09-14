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
create table student(rollno int(4), name varchar(50), age int(2), address varchar(10), phoneno int(10));
```
### OUTPUT:
![image](https://github.com/Ronick2005/F2_DBMS/assets/83219341/7e9351ab-b1f8-48eb-b31b-1dcf696615b7)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add column department varchar(4);
```
### OUTPUT:
![image](https://github.com/Ronick2005/F2_DBMS/assets/83219341/49914bce-5ecc-4033-979a-ef3b984f5331)


### 3) Drop the student table
 
### SQL QUERY: 
```

```
### OUTPUT:


### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```
### OUTPUT:
![image](https://github.com/Ronick2005/F2_DBMS/assets/83219341/cc616c76-f512-40eb-a11b-bf9af8c2d4b6)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```

```
### OUTPUT:
