# 🎓 Student Management System (Full Stack)

A full-stack web application to manage student records with secure authentication, built using **React, Spring Boot, and MySQL**. The system allows users to perform CRUD operations on student data with a scalable and production-ready architecture.

---

## 🚀 Live Demo

* 🌐 Frontend:[Live Website Link](https://student-management-system-by-rounak.netlify.app/)

---

## 📦 GitHub Repositories

* 🔗 Frontend:[ Frontend Repository Link](https://github.com/Rounak2811/Student-Management-System-react-frontend))
* 🔗 Backend: [Backend Repository Link](https://github.com/Rounak2811/Student-Management-System-springboot-backend)

---

## 🧠 Features

* 🔐 JWT-based Authentication & Authorization
* 👤 Role-based Access Control (Admin/User)
* 📋 Add, Update, Delete, View Student Records
* 🔍 Search, Filter & Pagination for large datasets
* ⚡ RESTful API architecture
* 🛡️ Secure API communication with CORS configuration
* 📊 Clean UI with responsive design

---

## 🏗️ Tech Stack

### Frontend

* React.js
* Tailwind CSS

### Backend

* Spring Boot
* Spring Security (JWT Authentication)
* JPA / Hibernate

### Database

* MySQL (Hosted on cloud)

### Deployment

* Frontend hosted on **Netlify**
* Backend hosted on **Render**
* Database managed on **Aiven**

---

## 🧩 System Architecture

```
[ User Browser ]
        |
        v
[ React Frontend (Netlify) ]
        |
        |  HTTPS API Calls
        v
[ Spring Boot Backend (Render) ]
        |
        v
[ MySQL Database (Aiven) ]
```

---

## ⚙️ Backend Architecture

```
Controller → Service → Repository → Database
```

* **Controller**: Handles HTTP requests
* **Service**: Business logic
* **Repository**: Database interaction using JPA

---

## 🔐 Authentication Flow

1. User logs in → credentials verified
2. JWT token generated
3. Token sent with every API request
4. Backend validates token before granting access

---

## 📡 API Highlights

* `POST /auth/login` → Authenticate user
* `GET /students` → Fetch all students
* `POST /students` → Add new student
* `PUT /students/{id}` → Update student
* `DELETE /students/{id}` → Delete student

---

## 🛠️ Setup Instructions

### Backend

```bash
cd backend
mvn spring-boot:run
```

### Frontend

```bash
cd frontend
npm install
npm start
```

---

## 🧪 Testing

* API testing done using Postman
* Manual UI testing for user flows

---

## 🌟 Future Improvements

* File upload (student documents)
* Email notifications
* Dashboard analytics
* Caching using Redis

---

## 👨‍💻 Author

**Rounak Kumar**
