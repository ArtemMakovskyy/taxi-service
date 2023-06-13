# Taxi Service project.

### Description: Application for managing cars and drivers for taxi service with registration and authentication.

## Function description
 - Registration of driver
 - Authentication of driver
 - Login out
 - Creation of: manufacturers, drivers, cars.
 - Deleting: manufacturers, drivers, cars.
 - Display all: manufacturers, drivers, cars, cars by driver.
 - Adding driver to car.

## Project structure
    * main
        * java
            * taxi
                * controller - contains controllers
                * dao - sql queries
                * exception - project exceptions
                * lib - injector
                * model - entities
                * service - logic part of project
                * util - connection to db
                * web
                    * filter - authentication filter
            * resources
                * init_db.sql - creations of SQL tables
            * webapp
                * WEB-INF
                    * views - jsp pages & css
                * web.xml - connecting controllers to jsp pages
    

## Used technologies
- JAVA 11
- Maven
- Tomcat 9.0.75
- Dependency Injection
- HttpServlet
- AuthenticationService
- Filter
- MySQL
- JDBC
- JCP
- Git
- HTML
- CSS

## Instructions for running
1. Clone application from https://github.com/ArtemMakovskyy/taxi-service
2. Create sql tables with folder resources/init_db.sql
3. Fill fields: user, passwords, url to db and jdbc driver in util/ConnectionUtil
4. Connect and configure Tomcat 
5. Start the taxi service application with Tomcat




