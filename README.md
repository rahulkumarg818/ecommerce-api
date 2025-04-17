Spring Boot E-Commerce API

Description

This is a simple E-commerce REST API built using Spring Boot. It provides basic functionalities like product management and user authentication for an e-commerce platform.

Features

- User registration and login
- Product management (CRUD operations)
- Access control with roles (Admin, User)

Technologies Used

- Java 17
- Spring Boot
- Spring Data JPA
- MySQL (Database)
- RESTful APIs
- Maven

Installation

1.Clone the Repository
bash--
git clone https://github.com/rahulkumarg818/ecommerce-api.git

2. Install dependencies
Navigate to the project folder and run the following:
mvn clean install

3. Configure the database
Make sure to configure the MySQL database in application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=your_db_username
spring.datasource.password=your_db_password

4. Run the Application
To run the application:
mvn spring-boot:run
The application will start on http://localhost:8080.

API Documentation

1. POST /api/auth/register
Register a new user.
2. POST /api/auth/login
User login and authentication.
3. GET /api/products
Get all products.
4. POST /api/products
Add a new product.

Author
Rahul Kumar
GitHub: rahulkumarg818
