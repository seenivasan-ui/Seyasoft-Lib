# 📚 Library Management System

A full‑stack **Library Management System** built using **Spring Boot (Backend)** and **Angular (Frontend)**. This project allows users to manage **book categories**, **books**, and perform **CRUD operations** with validations. It is suitable for **learning**, **college projects**, and **interview demonstrations**.

---

## 🚀 Features

### 📂 Category Management

* Add new categories
* View all categories
* Update category details
* Delete categories
* Category name must be **unique**

### 📘 Book Management

* Add new books
* View all books
* Update book details
* Delete books
* Assign books to categories
* ISBN must be **unique**

### 🔍 Search & Filter

* Filter books by category
* Search books by name or author

### ✅ Validation & Error Handling

* Backend validation using Spring Validation
* Proper exception handling with meaningful messages

---

## 🛠️ Tech Stack

### Backend (Spring Boot)

* Java 17
* Spring Boot 3.x
* Spring Data JPA
* Hibernate
* H2 / MySQL Database
* Maven

### Frontend (Angular)

* Angular 15+
* TypeScript
* HTML5 / CSS3
* PrimeNG / Bootstrap (optional)

---

## 📁 Project Structure

```
library-management-system/
│
├── backend/                 # Spring Boot application
│   ├── src/main/java
│   │   └── com.example.library
│   │       ├── controller
│   │       ├── service
│   │       ├── repository
│   │       ├── entity
│   │       └── exception
│   └── src/main/resources
│       └── application.properties
│
├── frontend/                # Angular application
│   ├── src/app
│   │   ├── components
│   │   ├── services
│   │   └── models
│   └── angular.json
│
└── README.md
```

---

## ⚙️ Backend Setup (Spring Boot)

### Prerequisites

* Java 17 installed
* Maven installed

### Steps to Run Backend

```bash
cd backend
./mvnw spring-boot:run
```

Backend will start at:

```
http://localhost:8080
```

### H2 Console (Optional)

```
http://localhost:8080/h2-console
```

---

## ⚙️ Frontend Setup (Angular)

### Prerequisites

* Node.js (LTS)
* Angular CLI

### Steps to Run Frontend

```bash
cd frontend
npm install
ng serve
```

Frontend will start at:

```
http://localhost:4200
```

---

## 🌍 Deployment (Optional)

### Frontend

* Netlify / Render (Static Site)

### Backend

* Render / Railway / Fly.io

---

## 📌 API Endpoints (Sample)

### Category APIs

```
GET    /api/categories
POST   /api/categories
PUT    /api/categories/{id}
DELETE /api/categories/{id}
```

### Book APIs

```
GET    /api/books
POST   /api/books
PUT    /api/books/{id}
DELETE /api/books/{id}
GET    /api/books/category/{categoryId}
```

---

## 🎯 Use Cases

* College / Academic Project
* Full‑Stack Practice
* Spring Boot + Angular Learning
* Interview Demonstration Project

---

## 🤝 Contributing

Pull requests are welcome. Feel free to fork this repository and improve it.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Seenivasan**
GitHub: [https://github.com/your-username](https://github.com/seenivasan-ui)

---

⭐ If you like this project, don’t forget to star the repository!
