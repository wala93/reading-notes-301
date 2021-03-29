# SQL 

SQL:  (Structured Query Language) is a language allow us to  manipulate,and transform data from a relational database. 
SQL databases provide safe and scalable storage for millions of websites and mobile applications.

SQL databases including SQLite, MySQL, Postgres, Oracle and Microsoft SQL Server .

THE BASIC STRUCTUE OF database is table with fixed number of  colomn and unlimit number of rows 
we can select the spesific data from table in this formula :

SELECT *** FROM **; 

( *** ): the name of specific colomn

 ( ** ): the name of table 
 
 **********************************************************************************************************************
 INSERT INTO table_name
VALUES (value_1, value_2,....) 

allow you to insert new row with its values 

*********************************************************************************************************************
if we want  to filter results from being returned, we need to use a WHERE clause in the query.
like this syntax :

SELECT column, another_column, …
FROM mytable
WHERE condition
    AND/OR another_condition
    AND/OR …;
