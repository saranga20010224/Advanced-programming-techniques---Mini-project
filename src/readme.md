## Student Management Application

## Setup Instructions

1. **Create the MySQL Database:**
   - Open MySQL Workbench.
   - Run:
     
     CREATE DATABASE student;
     USE student;
     CREATE TABLE student_details (
         rollnum INT PRIMARY KEY,
         sname VARCHAR(100),
         clgname VARCHAR(100),
         city VARCHAR(100),
         percentage FLOAT );
     

2. **Set up project:**
   - Ensure the MySQL JDBC driver is added to classpath.
     
     String user="root";
     String pass="12345";
     

3. **Build and Run:**
   - Compile and run the `client.java` main class.

## Assumptions 

- Tested on MySQL 8 and Java 8+.
- The MySQL server must be running on `localhost:3306`.
