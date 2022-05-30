# TAXI-SERVICE
This project is a prototype of a taxi service. It was created using technologies that you can find below.

___
## Features

* Authorization using login, password
* Viewing main menu


* Creating car manufacturer
* Deleting car manufacturer
* Viewing all car manufacturers
* Adding a specific driver to the car


* Creating car with manufacturer
* Deleting car
* Viewing all cars


* Creating new driver
* Deleting driver
* Viewing all drivers

___
## Project structure
This project is built by 3-tier architecture:

- Controllers layer
- Service layer
- Data access layer

### Database relations
![relation](images/database_relations.png)
___
## Technologies
- Java 11
- MySql
- JDBC
- JSP, JSTL
- Logback
- Apache Tomcat
- Maven

___
## How to run project
1. Install MySQL
2. Install Tomcat 9 version
3. Clone it to your IDE
4. Use database_init.sql file to initialize your database
5. Open ConnectionUtil.class then add url, login and password from your DB. Configure JDBC driver
6. Run this project using Tomcat.
