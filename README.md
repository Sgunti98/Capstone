
# Employee Management System

The Employee management System is a web application developed using Spring Boot, incorporating security features, and utilizing Thymeleaf for templating. This readme file provides an overview of the application, its features, and instructions on how to set up and run the application.

# Table of Contents

Introduction

Installation

Usage

Technologies Used

License

# Introduction

The Employee management system is an interactive web application that allows admins to add new employees, save them, and update/delete the employee information. There is also a search to find the specific employee details if there are multiple records.. This readme file provides an overview of the EMS, its features, and instructions on how to set up and run the application. It is built using the Spring Boot framework, which allows for rapid development and easy integration with various components. Thymeleaf is utilized for server-side templating, enabling dynamic content rendering on the client side.

# Installation

To install and run the Employee management System locally, follow these steps:

Clone the repository: git clone https://github.com/Sgunti98/Capstone
Navigate to the project directory: cd Ems-app
Set up the database: MySQL
Build the application: mvn clean package
Run the application: java -jar target/Ems-app.jar
Open your web browser and visit: http://localhost:8080

# Usage

Once the Ems App is running in your web browser, follow these steps to use the application:

Registration/Login: If you are a new user, click on the "Register" button to create an account. If you already have an account, click on the "Login" button to access the app.
Once you login click Add employee button to add the employees. Enter all the required fields and slect save employees. 
New employees will be displayed in the employees list.
You can perform update/delete on the employees list.
After you perform all the operations user can Logout.

# Technologies Used

The Ems is built using the following technologies:
 
Java with Spring Boot
Thymeleaf for server-side templating
Spring Security for user authentication and authorization
Database and Technology - MySQL, Hibernate ORM, JPA
HTML, CSS, JavaScript, Bootstrap for frontend

# License

The Ems App is open-source software. Feel free to modify and use the code according to the terms of the license.
