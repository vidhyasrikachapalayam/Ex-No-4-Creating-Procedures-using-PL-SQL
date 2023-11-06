# Ex. No: 4 Creating Procedures using PL/SQL
## date:5/9/23
## AIM: 
To create a procedure using PL/SQL.

## Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

## Program:

## Program To Create Table:
```
create table employee2 (empid NUMBER, empname VARCHAR(20), dept VARCHAR(10),salary NUMBER);
```
## Program To Create Procedure:
```
create or replace procedure insert_employee_data is
begin
insert into employee2 values(1,'priya','IT',10000);
insert into employee2 values(2,'vijis','aids',25000);
insert into  employee2 values(3,'thilaga','iot',50000);
insert into employee2 values(4,'prabha','cse',70000);
COMMIT;
END;
/
```
## Program To Call The Procedure:
```
execute inserting_data;
```
## Program To Display The Table:
```
select * from employee2;
```
## Output:
![image](https://github.com/vidhyasrikachapalayam/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119477817/2680f7ad-6c65-4586-ab31-c4be03a449a0)


## Result:
  Hence procedure has been created using PL/SQL.
