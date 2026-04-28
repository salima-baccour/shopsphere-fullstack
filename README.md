# 🛒 ShopSphere – Full Stack E-Commerce Platform

ShopSphere is a modern full-stack e-commerce web application built using **Spring Boot** for the backend and **ReactJS** for the frontend.
The project demonstrates how to design a scalable RESTful API and integrate it with a dynamic, responsive user interface.

---

## 🚀 Overview

This application was developed to showcase full-stack development skills through:

* Structured backend architecture (Controller / Service / Repository)
* RESTful API design and integration
* Dynamic frontend rendering with React
* Clean and maintainable project organization

---

## 🏗️ Project Structure

```
ShopSphere/
├── backend-service/   # Spring Boot API (business logic & database)
└── frontend-app/      # ReactJS application (UI layer)
```

---

## ⚙️ Tech Stack

### 🔹 Backend

* Java 17
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL
* Maven

### 🔹 Frontend

* ReactJS
* Vite
* Axios
* Bootstrap
* JavaScript (ES6+)

---

## ✨ Features

* 📦 Product management (Create, Read, Update, Delete)
* 🔗 REST API communication between frontend and backend
* ⚡ Fast development environment with Vite
* 🎨 Responsive and clean UI
* 🗄️ MySQL database integration
* 🧩 Modular and scalable architecture

---

## 🔌 API Endpoints

| Method | Endpoint       | Description           |
| ------ | -------------- | --------------------- |
| GET    | /products      | Retrieve all products |
| GET    | /products/{id} | Get product by ID     |
| POST   | /products      | Create new product    |
| PUT    | /products/{id} | Update product        |
| DELETE | /products/{id} | Delete product        |

---

## 🛠️ Installation & Setup

### 📌 Backend

```bash
cd backend-service
mvn clean install
mvn spring-boot:run
```

Configure database in:

```
src/main/resources/application.properties
```

Example configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

---

### 💻 Frontend

```bash
cd frontend-app
npm install
npm run dev
```

The application will be available at:

```
http://localhost:5173
```

---

## 🔗 Backend Connection

Make sure your frontend calls the backend correctly:

```javascript
axios.get('http://localhost:8080/products')
```

---

## 📈 Project Highlights

* Full-stack web development
* REST API design with Spring Boot
* Frontend architecture using React
* Integration of backend and frontend layers
* Clean code practices and modular design

---

## 🚀 Future Enhancements

* 🛒 Shopping cart and checkout system
* 🔐 Authentication & authorization (JWT / Keycloak)
* 💳 Online payment integration
* 📊 Admin dashboard with analytics
* 🤖 AI-based product recommendations

---

## 👩‍💻 Author

**Baccour Salima**
Software Engineering Student | Full-Stack Developer

---

## ⭐ Conclusion

ShopSphere is a solid foundation for building real-world e-commerce applications.
It reflects best practices in full-stack development and demonstrates the integration of modern technologies in a professional environment.
