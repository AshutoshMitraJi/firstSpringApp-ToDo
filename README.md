## ToDo App - Spring Boot Mini Project
This project is a simple ToDo Application developed using Java and Spring Boot. It showcases CRUD operations through RESTful APIs and demonstrates the use of MVC architecture in a real-world backend service. It was built as part of my journey into enterprise Java development.

### Features:
Add new tasks
View all tasks
Update the completion status of tasks
Delete tasks
Uses H2 in-memory database for development/testing
Clean architecture with Controller, Service, Repository layers
RESTful API design with proper HTTP methods
Optional Swagger UI integration for documentation

### Tech Stack:
Java
Spring Boot
Maven
H2 Database (In-Memory)
Visual Studio Code
Postman / Swagger UI for API testing

### API Endpoints:
GET /tasks – Retrieve all tasks
POST /tasks – Create a new task
PUT /tasks/{id} – Update a task by ID
DELETE /tasks/{id} – Delete a task by ID

### How to Run:
Clone the repository:
git clone https://github.com/AshutoshMitraJi/todo-app.git
Navigate into the project:
cd todo-app
Build the application:
mvn clean install
Run the Spring Boot app:
mvn spring-boot:run
Open Postman or your browser:
http://localhost:8080/tasks

### Future Enhancements:
Integrate with a frontend using Angular
Add user authentication with Spring Security
Replace H2 with MySQL or PostgreSQL for production use
Implement UI for task management and analytics dashboard
