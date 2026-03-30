# Easy School Management System (Spring Boot)

## 🚀 Overview
Easy School is a Spring Boot-based web application designed to manage school operations such as student management, user profiles, courses, contacts, and administration functionalities.

The application follows a layered architecture using Controller, Service, Repository, and Model layers for clean and maintainable code.

---

## 🎯 Features
- Student Management
- Login & Authentication
- Profile Management
- Course Management
- Contact Management
- Admin Dashboard
- Holiday Management
- Global Exception Handling
- Role-based access control
- Validation handling

---

## 🏗️ Project Architecture

### Controller Layer
Handles HTTP requests and responses.

Controllers:
- AdminController
- ContactController
- DashboardController
- GlobalExceptionController
- HolidaysController
- HomeController
- LoginController
- ProfileController
- PublicController
- StudentController

---

### Service Layer
Contains business logic.

Responsibilities:
- Process application logic
- Validate data
- Handle operations between controller and repository

---

### Repository Layer
Handles database operations using Spring Data JPA.

Responsibilities:
- Save data
- Fetch data
- Update data
- Delete data

---

### Model (Entity) Layer
Represents database tables.

Entities:
- Address
- BaseEntity
- Contact
- Courses
- EazyClass
- Holiday
- Person
- Profile
- Roles

---

### Configuration Layer
Handles application configuration.

- ProjectSecurityConfig
- WebConfig

---

### Additional Components
- Constants → EazySchoolConstants
- AOP → Logging & cross-cutting concerns
- Audit → Tracks data changes
- Validation → Input validations

---

## 🛠️ Technologies Used
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- MySQL / H2 Database
- Maven
- IntelliJ IDEA
- Git & GitHub

---

## 🔄 Application Flow
1. Client sends request to Controller
2. Controller calls Service layer
3. Service processes business logic
4. Repository interacts with a database
5. Response returned to client

---

## ▶️ How to Run
1. Clone the repository  
   git clone https://github.com/arumulla/EasyShoolSpringbootProject

2. Open project in IntelliJ IDEA

3. Configure database in `application.properties`

4. Run:
   EasySchoolApplication.java

5. Access application via browser or Postman

---

## 🔐 Security
- Implemented Spring Security
- Role-based authentication
- Login handling using controllers

---

## 📌 Future Enhancements
- JWT Authentication
- Swagger API documentation
- Docker deployment
- Cloud deployment (AWS)
- Microservices architecture

---

## 👨‍💻 Author
Eshwar Arumulla

GitHub: https://github.com/arumulla