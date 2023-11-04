# Hotel-Management-System
Developed a graphical user interface based on Java Swing for managing hotel operations, including room booking, billing, and customer management. Utilized MySql to store and retrieve data

//DataBase Connectivity you need to do externally..
Database [ hotelmanagementsystem ]
Tables [ customer, department, driver, employee, login, room ]...

//Firstly download the mysql connector jar file and add to the your java application... after that follw the below steps...

instructions from here you need to follow..

//Creating database in the mysql workbench...
create database hotelmanagementsystem;

//Creating the tables in the hotelmanagementsystem database...
1. creating the customer table.
   create table customer(
           document varchar(20),
           number varchar(30),
           name varchar(30),
           gender varchar(15),
           country varchar(20),
           room varchar(10),
           checkintime varchar(80),
           deposit varchar(20)
   );

2. creating the department table.
   create table department(
           department varchar(30),
           budget varchar(30)
   );

3. creating the driver table.
    create table driver(
           name varchar(20),
           age varchar(10),
           gender varchar(15),
           company varchar(20),
           brand varchar(20),
           available varchar(20),
           location varchar(40)
     );

4.creating the login table.
    create table login( 
            username varchar(25), 
            password varchar(25) 
    );
    //Insert this bcs of the login purpose username and password..
         insert into login values('admin','1234');

5. creating the room table.
      create table room(
             roomnumber varchar(10),
             availability varchar(20),
             cleaning_status varchar(20),
             price varchar(20),
             bed_type varchar(20)
       );

6. creating the employee table..
       create table employee(
               name varchar(25),
               age varchar(10),
               gender varchar(15),
               job varchar(30),
               salary varchar(30),
               phone varchar(15),
               email varchar(40),
               aadhar varchar(20)
       );

   //Now its ready to use.... Thank you for u r interest in this project...
         










