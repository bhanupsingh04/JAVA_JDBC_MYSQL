# JAVA_JDBC_MYSQL

# Java JDBC CRUD Application with MySQL

A simple and practical Java application demonstrating how to perform **CRUD operations (Create, Read, Update, Delete)** on a **MySQL database** using **JDBC (Java Database Connectivity)**.

This project is a great starting point for Java developers who want to learn how to integrate Java applications with databases for backend operations.

##  Overview

This application covers:

- Connecting a Java application with MySQL using JDBC
- Inserting data into a MySQL table
- Fetching and displaying records from the database
- Updating existing records
- Deleting records from the database
- Organized code structure with error handling

## Technologies Used

| Technology     | Purpose                        |
|----------------|--------------------------------|
| Java (JDK 8+)  | Programming language           |
| JDBC API       | Database connectivity          |
| MySQL          | Relational database            |
| Eclipse IDE    | Java development environment   |
| MySQL Workbench / CLI | Database GUI/Command line |

## Project Structure
JDBC-CRUD-Application/
│
├── src/
│ ├── DBConnection.java # JDBC connection setup
│ ├── InsertData.java # Code to insert data
│ ├── FetchData.java # Code to fetch and display data
│ ├── UpdateData.java # Code to update records
│ └── DeleteData.java # Code to delete records
│
├── db_config.sql # SQL script for table creation
├── README.md # Project documentation
└── .gitignore

## Create the database and table in MySQL:
Use the script db_config.sql to create the required table:

## CREATE DATABASE jdbc_demo;

USE jdbc_db;

CREATE TABLE register (
    name VARCHAR(100),
    post VARCHAR(100),
    email VARCHAR(100),
    salary VARCHAR(100),
    city VARCHAR(100),
);

## Configure your DB connection:
In DBConnection.java, update your:

String url = "jdbc:mysql://localhost:3306/jdbc_demo";
String user = "your_mysql_username";
String password = "your_mysql_password";

## Run the application:

Open the project in Eclipse

Compile and run each Java file as needed:

InsertData.java to insert new students

FetchData.java to retrieve and display records

UpdateData.java to modify data

DeleteData.java to remove records

## Output Example (Console)

=== Register ===
| Name:  | Post: Software Engineer | Email: bhanu122gmail.com| salary: 50,000 | City: Noida

## License
This project is licensed under the MIT License.
Feel free to fork, clone, and contribute!

🌟 Star this repo if it helped you, and stay connected for more such Java backend projects!
#Java #JDBC #MySQL #CRUD #JavaDeveloper #DatabaseIntegration #EclipseIDE #BackendDevelopment #StudentProject #JavaProject

Follow me on Linkedin--www.linkedin.com/in/bhanu-partap-singh-817394373






