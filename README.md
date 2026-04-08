# 🛒 E-Commerce Backend API (Spring Boot)

> A modular and scalable RESTful backend for an E-commerce platform built using Spring Boot.
> This project demonstrates real-world backend development including product management, cart operations, and order processing.

---

## 🚀 Overview

This project simulates a real-world E-commerce backend system.
It is designed using a clean layered architecture and focuses on building maintainable, scalable, and efficient REST APIs.

---

## ✨ Key Features

* 📦 Product Management (CRUD operations)
* 🛒 Cart Management System
* 📑 Order Processing
* 🔗 RESTful API Design
* 🧩 Layered Architecture (Controller → Service → Repository)
* ⚡ Fast in-memory database using H2
* 🛠️ Easy testing using API tools like Postman

---

## 🛠️ Tech Stack

| Category    | Technology        |
| ----------- | ----------------- |
| Language    | Java              |
| Framework   | Spring Boot       |
| ORM         | Spring Data JPA   |
| Database    | H2 (In-Memory DB) |
| Build Tool  | Maven             |
| API Testing | Postman           |

---

## 📂 Project Structure

```
src/main/java/com/yourpackage/
│
├── controller     # Handles HTTP requests
├── service        # Business logic layer
├── repository     # Data access layer
├── model          # Entity classes
├── dto            # Data Transfer Objects (optional)
└── exception      # Exception handling (if implemented)
```

---

## ⚙️ Getting Started

### 🔹 Prerequisites

* Java 17+
* Maven

---

### 🔹 Installation & Run

```bash
# Clone repository
git clone https://github.com/your-username/ecommerce-backend-springboot.git

# Navigate into project
cd ecommerce-backend-springboot

# Run application
mvn spring-boot:run
```

---

## 🗄️ H2 Database Console

Access the database UI in your browser:

```
http://localhost:8080/h2-console
```

### 🔑 Default Configuration

| Property | Value                |
| -------- | -------------------- |
| JDBC URL | `jdbc:h2:mem:testdb` |
| Username | `sa`                 |
| Password | *(leave empty)*      |

---

## 🔌 API Endpoints (Sample)

### 📦 Product APIs

| Method | Endpoint       | Description       |
| ------ | -------------- | ----------------- |
| GET    | /products      | Get all products  |
| GET    | /products/{id} | Get product by ID |
| POST   | /products      | Add new product   |
| PUT    | /products/{id} | Update product    |
| DELETE | /products/{id} | Delete product    |

---

### 🛒 Cart APIs

| Method | Endpoint     | Description           |
| ------ | ------------ | --------------------- |
| GET    | /cart        | View cart             |
| POST   | /cart/add    | Add item to cart      |
| DELETE | /cart/remove | Remove item from cart |

---

### 📑 Order APIs

| Method | Endpoint | Description    |
| ------ | -------- | -------------- |
| POST   | /orders  | Place order    |
| GET    | /orders  | Get all orders |

---

## ⚠️ Limitations

* ❌ Authentication & Authorization not implemented yet
* ❌ Data is not persistent (resets on restart due to H2)
* ❌ No frontend (backend-only project)

---

## 🔮 Future Enhancements

* 🔐 Add Spring Security + JWT Authentication
* 🗄️ Migrate to MySQL/PostgreSQL (production-ready)
* 🌐 Build frontend (React)
* ☁️ Deploy using Docker & AWS
* 📊 Add logging and monitoring

---

## 🧠 Learning Outcomes

* REST API development using Spring Boot
* Backend architecture design
* Database operations with JPA & Hibernate
* Real-world application flow (cart → order system)

---

## 👨‍💻 Author

**Sumit Kumar**
🎓 Final Year Computer Science Student
💡 Aspiring Java Backend Developer

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📜 License

This project is licensed under the MIT License.
