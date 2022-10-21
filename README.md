# Major-Projects
Student Result System-
- Built a Student Result management system GUI application to help the admin store various data such as course result declaration , student details and to help student's check their own result.
- Added functionaly for admin to add/list student detail , add/list/update student result and for student to search for their result.
- There is an admin login panel as well.
- Used mysql database to store/fetch data entered into the GUI.
- Made the application using java swing, awt and mysql database.

- Create Database name as studentresultsystem;
- Create following tables in above database-
- CREATE TABLE student(name VARCHAR(100), rollNo VARCHAR(10) PRIMARY KEY, gender VARCHAR(6), fathername VARCHAR(40), courseName VARCHAR(10), branchName VARCHAR(20));
- CREATE TABLE result(rollNo VARCHAR(10) PRIMARY KEY, physics INT, maths INT,electrical INT,civil INT, chemistry INT , total INT);
- CREATE TABLE admindata(id INT PRIMARY KEY auto_increment,username VARCHAR(50) UNIQUE,password VARCHAR(255),created_at datetime CURRENT_TIMESTAMP);
- INSERT INTO  admindata (username,password) VALUES ('root','root');
