# beststore.com

BestStore - Product Management System
BestStore is a project that allows users to perform CRUD (Create, Read, Update, Delete) operations on different products. It is built using Spring Boot, Spring MVC, MySQL, and Thymeleaf. This README provides instructions for setting up and running the project using Eclipse IDE for coding and MySQL for the database.

Requirements:-
Before running the project, ensure you have the following installed:

Java: JDK 8 or higher.
Eclipse IDE: For coding and running the project.
MySQL Database: For storing data.
Maven: For managing dependencies.

Import the project into Eclipse:
Open Eclipse IDE.
Click on File -> Import.
Select Existing Maven Projects.
Browse to the directory where you cloned the repository and select the project.

Configure the MySQL database:
Create a MySQL database and update the application.properties file with your database credentials:

spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password

Run the application:
Right-click on the project in Eclipse.
Select Run As -> Spring Boot App.

Access the application:
Open a web browser.
Enter the following URL: http://localhost:8080


Memory updated
BestStore - Product Management System
BestStore is a project that allows users to perform CRUD (Create, Read, Update, Delete) operations on different products. It is built using Spring Boot, Spring MVC, MySQL, and Thymeleaf. This README provides instructions for setting up and running the project using Eclipse IDE for coding and MySQL for the database.

Requirements
Before running the project, ensure you have the following installed:

Java: JDK 8 or higher.
Eclipse IDE: For coding and running the project.
MySQL Database: For storing data.
Maven: For managing dependencies.
Setup
Follow these steps to set up and run the project:

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/beststore.git
Import the project into Eclipse:
Open Eclipse IDE.
Click on File -> Import.
Select Existing Maven Projects.
Browse to the directory where you cloned the repository and select the project.
Configure the MySQL database:
Create a MySQL database and update the application.properties file with your database credentials:
bash
Copy code
spring.datasource.url=jdbc:mysql://localhost:3306/your_database
spring.datasource.username=your_username
spring.datasource.password=your_password
Run the application:
Right-click on the project in Eclipse.
Select Run As -> Spring Boot App.
Access the application:
Open a web browser.
Enter the following URL: http://localhost:8080

Usage:-
Create: Click on the "Add Product" button and fill out the form.
Read: View the list of products on the homepage and click on a product to view its details.
Update: Click on the "Edit" button next to a product and modify the details.
Delete: Click on the "Delete" button next to a product to remove it from the database.

Here are some images of the project:-

Product List:-


![productList](https://github.com/Yumn1503/beststore.com/assets/142492711/3dd01b54-daab-4990-9d5d-6e7fb76f694c)

Create Product:-


![createpro](https://github.com/Yumn1503/beststore.com/assets/142492711/8089a70d-ef90-432a-a01a-78a1c0f1caf0)

Edit Product:-


![edit_pro](https://github.com/Yumn1503/beststore.com/assets/142492711/ebc507d9-3a42-42a6-82cd-b6da23017ebf)


















