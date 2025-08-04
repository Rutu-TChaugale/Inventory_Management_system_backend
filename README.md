# Inventory Management System - Backend

🖥️ **Overview**

This is the backend REST API for the Inventory Management System built using Spring Boot.
It provides all the necessary endpoints to manage products, categories, suppliers, purchases, sales, and user authentication.

---

## 🔧 Setup Instructions

### ✅ Prerequisites

* Java 17+ or compatible JDK installed
* Maven installed (for dependency management and build)
* MySQL installed and running
* Backend API will run on: `http://localhost:8080/`

---

## 🛠️ Installation & Running Backend

```bash
git clone [https://github.com/Rutu-TChaugale/Inventory_Management_system_backend.git]
cd Inventory-Management-System
```

1. Open the project in your favorite IDE (Eclipse, IntelliJ, VSCode).
2. Configure the MySQL database connection in `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/inventory_db
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update
```

3. Make sure the database `inventory_db0` exists. If not, create it using:

```sql
CREATE DATABASE inventory_db;
```

4. Run the application using your IDE or with:

```bash
mvn spring-boot:run
```

---

## 🔗 Frontend Repo

Make sure to clone and run the frontend application separately for the full system:


🔗 Frontend Repo: [frontend (Angular)](https://github.com/Rutu-TChaugale/Inventory_Management_system_frontend.git)


---

## 📚 Technologies Used

* Java 17+
* Spring Boot (Web, Data JPA, Security)
* Hibernate ORM
* MySQL
* Maven

---

## ✍️ Author

**Rutika Chaugale**
📧 [chaugalerutu7770@gmail.com](mailto:chaugalerutu7770@gmail.com)

---

