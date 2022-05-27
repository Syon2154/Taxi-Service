# TAXI-SERVICE
This project is the simple taxi service application's analogue with driver's authentication.

___
## Features

* Authorization using login, password
* View main menu
* 
* Creating car manufacturer
* Deleting car manufacturer
* View all car manufacturers
* Adding a specific driver to the car

* Creating car with manufacturer
* Deleting car
* View all cars

* Creating new driver
* Deleting driver
* View all drivers

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
