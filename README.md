# Student Management REST API

A simple backend **REST API built using Spring Boot** for managing student records.  
This project demonstrates core backend development concepts such as RESTful API design, layered architecture, JSON request handling, and API testing using Postman.

---

## Technologies Used

- Java
- Spring Boot
- Maven
- Postman
- Git & GitHub

---

## Project Architecture

The application follows a **layered architecture**:

Controller → Service → Data (In-Memory List)

- **Controller Layer** – Handles HTTP requests and responses  
- **Service Layer** – Contains business logic for managing students  
- **Data Layer** – Stores student records in an in-memory list

---

## Project Structure

```
student-management-api
│
├── controller
│   └── StudentController.java
│
├── service
│   └── StudentService.java
│
├── model
│   └── Student.java
│
└── BackenddemoApplication.java
```

---

## API Endpoints

### Create Student

```
POST /students
```

Example Request Body:

```json
{
  "id": 1,
  "name": "Sai Krishna",
  "age": 19,
  "department": "CSE Cyber Security"
}
```

---

### Get All Students

```
GET /students
```

Returns a list of all student records.

---

### Get Student by ID

```
GET /students/{id}
```

Example:

```
GET /students/1
```

Returns the student details for the specified ID.

---

### Update Student

```
PUT /students/{id}
```

Updates an existing student's information.

---

### Delete Student

```
DELETE /students/{id}
```

Deletes a student record by ID.

---

## Running the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Sai-Krishna-131006/student-management-api
```

### 2. Open the Project

Open the project in **IntelliJ IDEA** or any Java IDE.

### 3. Run the Application

Run the main class:

```
BackenddemoApplication.java
```

### 4. Test the APIs

Use **Postman** or a browser to test the endpoints.

---

## Server

The application runs locally on:

```
http://localhost:8081
```

---

## What This Project Demonstrates

- REST API development using Spring Boot
- CRUD operations using HTTP methods (GET, POST, PUT, DELETE)
- Layered backend architecture
- JSON request and response handling
- API testing using Postman
- Version control using Git and GitHub

---

## Author

**Sai Krishna**  
GitHub: https://github.com/Sai-Krishna-131006
