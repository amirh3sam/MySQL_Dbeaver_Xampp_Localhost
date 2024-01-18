# CreateDataBase_Localhost


  ![mysql](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/eae125f8-e240-4c90-9017-23ca62ae8a46)


Set up a local MySQL server effortlessly with this guide, perfect for practicing MySQL scripts without the need for an external server. Simply install XAMPP and DBeaver, and you're ready to run your SQL queries and hone your skills as much as you desire.

create connection:

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/3578cb50-f98d-4f6f-a542-c1fed9482d5c)

click mySQL dataBase:

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/9383b9b6-c56e-4a67-8db7-174125e8d9ab)

leave the setting like the picture bloew

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/bdbd7da7-7166-423f-bc0a-59c9bd78a314)

if ask to download click download 

right click on database and create dataBase

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/15fb766d-e4f5-4334-b99e-e25b176e619d)

after you create database right click on your database and SQL editor then Open SQL script

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/f90f8b72-efd7-4e57-948c-82ca9f00dbbc)

this is one way that you can start create tables and insert data into it and retrived the data: 

if we want to create the table by typying the script is a good practive to do...

 The MySQL CREATE TABLE Statement:
 ```Javascript
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
   ....
);
```
for example we can do :

```Javascript
CREATE TABLE Persons (
    PersonID int,
    LastName varchar(255),
    FirstName varchar(255),
    Address varchar(255),
    City varchar(255)
);
```
![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/283f9ea0-9da1-47c6-ab92-61e00e65c7e8)

and run the code

after you run the code you will see this 

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/572aa68d-6145-43ab-a933-eea5465b440d)


now its time to insert :The MySQL INSERT INTO Statement:

```Javascript
INSERT INTO table_name (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);
```

for example :

```Javascript
INSERT INTO Persons (CustomerName, ContactName, Address, City, PostalCode, Country)
VALUES ('Cardinal', 'Tom B. Erichsen', 'Skagen 21', 'Stavanger', '4006', 'Norway');
```
![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/cde0f907-1898-4a30-b96d-272e41996b75)

 then run the code now we add our first data into the table .

 now we can retrive the data :
 
 ``` SELECT * FROM PERSONS;```

 ![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/1d04f0f6-7f25-4ee8-a0db-3c1b654645fd)



second way is through your browser click on admin infront of SQL


![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/3aff9540-b909-417e-b7d2-43e5064e6952)


you can select your database :

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/d8662b1b-e71d-4fcf-8c33-50a9c029c361)

you can create the table here and give the number of columns :

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/622c03f5-eea9-48a4-8774-04b743398031)

there is Insert tab that you can add data to your table 

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/0b9a53f6-d795-47da-8721-9e788a3a0ba6)


there is a structure tab that you can change your table variable ,add or remove from the table 

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/2f0b0131-6ee9-4f27-b918-9a9176a76681)

