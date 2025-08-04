🖥️ Inventory Management System - Backend
This is the backend REST API for the Inventory Management System, built using Spring Boot.
It provides endpoints to manage Products, Categories, Suppliers, Purchases, Sales, and User Authentication.

🔧 Setup Instructions
✅ Prerequisites
Java 17+ (or compatible JDK)

Maven

MySQL

IDE (Eclipse, IntelliJ, VSCode)

Backend runs at: http://localhost:8080/

🛠️ Installation & Running
bash
Copy
Edit
git clone https://github.com/spuffyffets/Inventory-Management-System.git
cd Inventory-Management-System
Step-by-Step:
Open the project in your IDE.

Configure MySQL database in src/main/resources/application.properties:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/inventory_db01
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update
Create the database (if not already present):

sql
Copy
Edit
CREATE DATABASE inventory_db01;
Run the project using your IDE or with the command:

bash
Copy
Edit
mvn spring-boot:run
🔗 Frontend Repository
Make sure to clone and run the frontend separately for full functionality.

Frontend (Angular): Frontend Repository <!-- Replace with actual link if available -->

📚 Technologies Used
Java 17+

Spring Boot (Web, Data JPA, Security)

Hibernate ORM

MySQL

Maven

✍️ Author
Rutika Chaugale
📧 chaugalerutu7770@gmail.com
