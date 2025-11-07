# 🪙 Credit Card Management System

## 📖 Overview
The **Credit Card Management System** is a Spring Boot-based backend application designed to manage customer credit card details, transactions, and user authentication securely.  
It provides REST APIs for credit card operations, customer management, and transaction history, ensuring a robust and secure experience using JWT-based authentication.

---

## 🧰 Tech Stack
- **Java 17+**
- **Spring Boot** (Web, Security, Data JPA)
- **MySQL / PostgreSQL** (Database)
- **Hibernate (JPA)**
- **JWT (JSON Web Token)** for Authentication
- **Swagger** for API Documentation
- **Lombok** for Boilerplate Reduction
- **Maven** for Build & Dependency Management

---

## ⚙️ Features
✅ User Registration & Login (JWT-based Authentication)  
✅ Role-based Access Control (Admin/User)  
✅ Credit Card CRUD Operations  
✅ Customer Management APIs  
✅ Transaction Tracking & Logs  
✅ Global Exception Handling  
✅ Data Validation  
✅ Swagger UI for API Testing  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yuvi-chavan/yuvi-chavan-CreditCardSystem.git
cd yuvi-chavan-CreditCardSystem
```

### 2️⃣ Configure the Database
Edit your `src/main/resources/application.properties` file:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/creditcard_db
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQL8Dialect
jwt.secret=yourSecretKey
```

### 3️⃣ Build & Run the Project
```bash
mvn clean install
mvn spring-boot:run
```

### 4️⃣ Access the Application
- **API Base URL:** `http://localhost:8080`
- **Swagger UI:** `http://localhost:8080/swagger-ui/index.html`

---

## 🧩 API Highlights

| Endpoint | Method | Description |
|-----------|---------|-------------|
| `/api/auth/register` | POST | Register a new user |
| `/api/auth/login` | POST | Login and get JWT token |
| `/api/customers` | GET/POST/PUT/DELETE | Manage customer data |
| `/api/creditcards` | GET/POST/PUT/DELETE | Manage credit card records |
| `/api/transactions` | GET/POST | Track transactions |

---

## 🧑‍💻 Author
**Yuvraj Chavan**  
💼 Java Backend Developer | 2025 CSE Passout  
📫 [GitHub](https://github.com/yuvi-chavan)
