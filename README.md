# 🏋️ Fitness Monolith Backend

A production-ready backend application built using Spring Boot, implementing JWT-based authentication, role-based authorization, and RESTful APIs for a fitness tracking system.

---

## 🚀 Features

* 🔐 JWT Authentication & Authorization
* 👤 User Registration & Login
* 🛡️ Role-Based Access Control (USER / ADMIN)
* 📊 Activity Tracking System
* 💡 Recommendation Feature
* ⚙️ Global Exception Handling
* 📄 Swagger API Documentation
* 🐳 Dockerized Application
* 🌐 Environment-Based Configuration

---

## 🛠️ Tech Stack

* Java 17/25
* Spring Boot
* Spring Security
* JWT (JSON Web Token)
* PostgreSQL (Neon DB)
* Hibernate / JPA
* Docker
* Swagger (OpenAPI)

---

## 📂 Project Structure

```
src/main/java/com/project/fitness
│
├── controller
├── service
├── repository
├── model
├── dto
├── security
├── config
├── exception
```

---

## ⚙️ Environment Variables

```bash
DB_URL=your_database_url
DB_USER=your_username
DB_PWD=your_password
```

---

## ▶️ Running the Application

### 1. Clone the repository

```bash
git clone https://github.com/theyashshelar/fitness-monolith.git
cd fitness-monolith
```

---

### 2. Build the project

```bash
./mvnw clean package
```

---

### 3. Run using Docker

```bash
docker build -t fitness-monolith .
docker run -p 8080:8080 \
-e DB_URL=$DB_URL \
-e DB_USER=$DB_USER \
-e DB_PWD=$DB_PWD \
fitness-monolith
```

---

## 📑 API Documentation

Swagger UI:

```
http://localhost:8080/swagger-ui.html
```

---

## 🎯 Future Improvements

* 🔁 Convert monolith to microservices architecture
* 🔄 Add refresh tokens
* 📈 Add monitoring & logging
* 🌍 Deploy on cloud (AWS / Render)

---

## 👨‍💻 Author

**Yash Shelar**
Backend Developer | Java | Spring Boot

---
