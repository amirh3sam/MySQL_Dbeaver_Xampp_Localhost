  # Create mySQL server on Localhost


  ![mysql](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/eae125f8-e240-4c90-9017-23ca62ae8a46)


Set up a local MySQL server effortlessly with this guide, perfect for practicing MySQL scripts without the need for an external server. Simply install XAMPP and DBeaver, and you're ready to run your SQL queries and hone your skills as much as you desire.


--> To download [Xampp CLICK HERE](https://www.apachefriends.org/download.html)

--> To download [Dbeaver CLICK HERE](https://dbeaver.io/download/)

After downloading both, 

START XAMPP CONTORL : make sure to click on "Start" in front of Apache and MySQL.

Now, your local server is running.

![image](https://github.com/amirh3sam/Create-_mySQL_server_on_Localhost/assets/69331074/f5bd9258-fac7-4505-b8e4-f64b6172bd66)

Now, you should have a screen that looks like this:

![image](https://github.com/amirh3sam/Create-_mySQL_server_on_Localhost/assets/69331074/627fe72c-8a92-498d-a5bd-4366a47944b6)


START Dbeaver :

-> Create connection:

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/3578cb50-f98d-4f6f-a542-c1fed9482d5c)

-> Click on the MySQL database.

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/9383b9b6-c56e-4a67-8db7-174125e8d9ab)

Keep the settings as shown in the image: the username is "root," no password is set, and the port is 3306.

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/bdbd7da7-7166-423f-bc0a-59c9bd78a314)


If prompted to download, click on the download option.

Right-click on the database and choose the option to create a new database.

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/15fb766d-e4f5-4334-b99e-e25b176e619d)

after you create database right click on your database and SQL editor then Open SQL script

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/f90f8b72-efd7-4e57-948c-82ca9f00dbbc)

This provides a method to initiate the creation of tables, insert data into them, and retrieve the stored information:

If we intend to create the table by typing the script, it is a good practice to do so.

 The MySQL CREATE TABLE Statement:
 ```Javascript
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
   ....
);
```
for example we can type this script  :

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

And run the code.

After executing the code, you will observe this.

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/572aa68d-6145-43ab-a933-eea5465b440d)


It's time to populate the table with data using the MySQL INSERT INTO statement

```Javascript
INSERT INTO table_name (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);
```

For example :

```Javascript
INSERT INTO Persons (CustomerName, ContactName, Address, City, PostalCode, Country)
VALUES ('Cardinal', 'Tom B. Erichsen', 'Skagen 21', 'Stavanger', '4006', 'Norway');
```

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/cde0f907-1898-4a30-b96d-272e41996b75)

Execute the code, and you'll successfully add our initial data into the table.

Now We can now fetch the data:
 
 ``` SELECT * FROM PERSONS;```

 ![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/1d04f0f6-7f25-4ee8-a0db-3c1b654645fd)


------> Another method is to open your web browser and click on "Admin" next to MYSQL in the XAMPP app.

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/3aff9540-b909-417e-b7d2-43e5064e6952)

Now you can select your database :

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/d8662b1b-e71d-4fcf-8c33-50a9c029c361)

-> You can establish the table here and specify the number of columns.

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/622c03f5-eea9-48a4-8774-04b743398031)

-> The Insert tab allows you to input data into your table.

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/0b9a53f6-d795-47da-8721-9e788a3a0ba6)


-> In the Structure tab, you have the flexibility to modify your table's Name, Type, Collation, Attributes, Null settings, and add or remove elements from the table 

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/2f0b0131-6ee9-4f27-b918-9a9176a76681)

-> SQL tab let us to type our queries :

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/5c4b2a2e-5700-41b1-a930-925c18e53c97)

After typing, press and hold Ctrl + Enter on your keyboard, or click the 'Go' button at the bottom of the screen:

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/7e82b873-0a45-4378-ac2c-ca60e58c56bd)

And it will lead you to a screen displaying the results:

![image](https://github.com/amirh3sam/CreateDataBase_Localhost/assets/69331074/180277fc-cae6-45e4-9071-993767f49b83)

In this scenario, DBeaver is not required either.

Good luck guys enjoy!

