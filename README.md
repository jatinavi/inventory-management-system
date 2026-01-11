📦 Inventory Management System
A Full Stack Inventory Management System built using Spring Boot and ReactJS, designed to demonstrate clean REST API development, frontend-backend integration, and enterprise-style application architecture.
🚀 Features
Create, Read, Update, Delete (CRUD) inventory items
RESTful API design using Spring Boot
Responsive frontend built with ReactJS
Secure backend architecture with layered design
Clean separation of concerns
Easily extendable for authentication, roles, and CI/CD
🏗️ Architecture
ReactJS (Frontend)
      |
      |  REST APIs (JSON)
      |
Spring Boot (Backend)
      |
Hibernate / JPA
      |
Relational Database
🛠️ Tech Stack
Backend
Java
Spring Boot
Spring MVC
Hibernate / JPA
Frontend
ReactJS
Axios
HTML, CSS, JavaScript
Database
Relational Database (configurable)
Tools
Git
Maven
Postman
📂 Project Structure
Backend
controller  -> REST API endpoints
service     -> Business logic
repository  -> Database access (JPA)
model       -> Entity classes
Frontend
components  -> UI components
services    -> API calls
pages       -> Application screens
⚙️ How to Run the Project
Backend
cd backend
mvn spring-boot:run
Backend runs on:
http://localhost:8080
Frontend
cd frontend
npm install
npm start
Frontend runs on:
http://localhost:3000
🔌 API Overview
Method	Endpoint	Description
GET	/api/items	Get all inventory items
POST	/api/items	Add new item
PUT	/api/items/{id}	Update item
DELETE	/api/items/{id}	Delete item
🎯 Future Enhancements
Role-based authentication (Admin / User)
JWT-based security
Oracle / PostgreSQL integration
Docker & CI/CD pipeline
Audit logging
🧠 Learning Outcomes
Full stack application development
REST API best practices
Frontend-backend integration
Clean code and modular design
Enterprise project structuring
👤 Author
Jatin Kumar Balchandani
GitHub: https://github.com/jatinavi
