# 📌 Task Management API (Spring Boot)

A backend REST API for managing tasks, built using Spring Boot. This project demonstrates CRUD operations, database integration, and RESTful service design.

---

## 🚀 Features
- Create a new task
- View all tasks
- Update task details
- Delete tasks
- Task status management (PENDING, COMPLETED)

---

## 🛠️ Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Hibernate
- Maven

---

## 📂 Project Structure
src/main/java/com/example/demo
│── controller # Handles API requests
│── service # Business logic
│── repository # Database operations
│── entity # Data models


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

### 2️⃣ Open in IntelliJ
- Open the project in IntelliJ IDEA

### 3️⃣ Configure Database
Update `application.properties`:


### 4️⃣ Run the Application
- Run the main class
- Server will start on:

- 
---

## 📬 API Endpoints

| Method | Endpoint        | Description          |
|--------|----------------|----------------------|
| GET    | /tasks         | Get all tasks        |
| GET    | /tasks/{id}    | Get task by ID       |
| POST   | /tasks         | Create new task      |
| PUT    | /tasks/{id}    | Update task          |
| DELETE | /tasks/{id}    | Delete task          |

---

## 🧪 API Testing
- Use Postman to test APIs
- Send JSON request bodies for POST/PUT

Example:{
"title": "Learn Spring Boot",
"description": "Practice REST APIs",
"status": "PENDING"
}


---

## 🔐 Important Notes
- Do not expose your real database password
- Use placeholders in configuration files

---

## 📌 Author
**Mahek Zaheer**  
Aspiring Java Backend Developer 🚀

---

## ⭐ Future Improvements
- Add authentication (JWT)
- Add user-specific tasks
- Deploy on cloud (AWS / Render)
