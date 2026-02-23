# Employee Management System (EMS)

A **Full Stack Web Application** built using **Spring Boot** and **React** to manage employee records efficiently.

---

## 🚀 Tech Stack

### 🔹 Backend

* Java
* Spring Boot
* Spring Data JPA (Hibernate)
* REST APIs

### 🔹 Frontend

* React JS
* Axios
* Bootstrap / CSS

### 🔹 Database

* MySQL

---

## ✨ Features

* ➕ Add Employee
* 📋 View Employees List
* ✏️ Update Employee Details
* ❌ Delete Employee
* 🔎 REST API Integration with React UI
* 🗄️ MySQL Database Connectivity
* 🔐 Layered Architecture (Controller → Service → Repository)

---

## 📂 Project Structure

ems/
│
├── backend (Spring Boot)
│ ├── controller
│ ├── service
│ ├── repository
│ ├── entity
│ └── security
│
├── frontend (React)
│ ├── components
│ ├── services
│ └── pages
│
└── database (MySQL)

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

git clone https://github.com/your-username/EMS-SpringBoot-React.git
cd EMS-SpringBoot-React

### 2️⃣ Backend Setup (Spring Boot)

Update `application.properties`:

spring.datasource.url=jdbc:mysql://localhost:3306/ems
spring.datasource.username=root
spring.datasource.password=yourpassword

Run:

mvn spring-boot:run

Backend runs on:
http://localhost:8080

### 3️⃣ Frontend Setup (React)

cd frontend
npm install
npm start

Frontend runs on:
http://localhost:3000

---

## 🔗 API Sample

GET /api/employees → Fetch all employees
POST /api/employees → Add employee
PUT /api/employees/{id} → Update employee
DELETE /api/employees/{id} → Delete employee

---

## 📸 Future Enhancements

* 🔐 Authentication (JWT / Spring Security)
* 🌐 Cloud Deployment (AWS / Railway)
* 📊 Dashboard Analytics
* 📁 File Upload Support

---

## 👨‍💻 Author

Developed as a Full Stack Project using Spring Boot & React.

---

## 📜 License

This project is for learning and academic purposes.
