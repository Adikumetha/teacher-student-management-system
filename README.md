🎓 TEACHER & STUDENT MANAGEMENT SYSTEM

A full-stack web application designed to manage teachers, students, and academic records in a structured and organized manner.
This system provides clean CRUD operations and enables institutions to maintain academic data efficiently using a layered backend architecture and a simple, responsive frontend interface.

<img width="1920" height="948" alt="StudentProject img" src="https://github.com/user-attachments/assets/5b570a77-fcfd-494f-af70-505e1000aff2" />

🚀 Features
👨‍🏫 Teacher Management

1. Add new teachers
2. Update teacher details
3. View teacher records
4. Delete teachers

🎓 Student Management

1. Add new students
2. Update student information
3. View student records
4. Delete students

🔗 Relationship Management

* Assign students to teachers
* Maintain structured academic records

🔎 Search & Filtering

1. Search teachers and students
2. Filter records for quick access

📊 User Interface

1. Clean and simple layout
2. Easy navigation between modules

🧰 Technology Stack
Backend:

* Java
* Spring Boot
* JPA / Hibernate
* MySQL
* Maven

Frontend:

* HTML
* CSS
* JavaScript

Development Tools:

1. IntelliJ IDEA
2. Git & GitHub

🏗️ Project Architecture
Backend Structure:

1. controller
2. service
3. repository
4. models
5. dto
6. exception

Frontend Structure:

1. index.html
2. teachers.html
3. students.html
4. css/
5. js/

The backend follows a layered architecture:

* Controller → Handles HTTP requests
* Service → Contains business logic
* Repository → Manages database interaction

⚙️ Installation & Setup

1️⃣ Database Setup

Create a MySQL database:

CREATE DATABASE teacher_student_db;

2️⃣ Configure Application

Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/teacher_student_db
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
spring.jpa.hibernate.ddl-auto=update

3️⃣ Run Backend
mvn spring-boot:run

Backend runs on:

http://localhost:8080

4️⃣ Run Frontend

Open index.html in your browser.

📘 Sample API Endpoints
Teacher APIs :

1. POST /teachers
2. GET /teachers
3. GET /teachers/{id}
4. PUT /teachers/{id}
5. DELETE /teachers/{id}

Student APIs

1. POST /students
2. GET /students
3. GET /students/{id}
4. PUT /students/{id}
5. DELETE /students/{id}

📊 Key Highlights

- Clean layered backend structure
- RESTful API implementation
- Database integration using JPA/Hibernate
- Modular and maintainable codebase
- Clear separation of concerns

📌 Author

Masthan Sharif Shaik

GitHub: https://github.com/MasthanSharifShaik
