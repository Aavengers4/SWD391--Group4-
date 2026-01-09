# Online Learning Platform

An online learning platform built with **Spring Boot**, **React**, and **MySQL**, supporting courses, lessons, assignments, learning progress tracking, and AI-assisted learning.

---

## Tech Stack

### Backend
- Java 17
- Spring Boot
- Spring Data JPA
- Spring Security (JWT)
- MySQL

### Frontend
- React
- Axios
- React Router

### AI Service
- Python (AI Assistant)
- REST API / LLM integration

### Tools
- Maven
- Git
- Postman

---

## Features

### User
- Register / Login
- Enroll in courses
- Watch lessons
- Submit assignments
- Track learning progress

### Instructor
- Create and manage courses
- Upload lessons and assignments
- View student progress

### AI Assistant
- Support app usage
- Help solve exercises
- Guide students step-by-step

---

## Database Design

Main entities:
- User
- Course
- CourseModule
- CourseSection
- Lesson
- Enrollment
- Assignment
- Submission
- LearningProgress
- AIInteraction

---

## Project Structure

backend/
- controller
- service
- repository
- entity
- dto
- security

frontend/
- components
- pages
- services
- hooks

---

## Installation & Setup

### 1. Clone repository
```bash
git clone https://github.com/your-repo/online-learning.git
```

### 2. Create database
```sql
CREATE DATABASE online_learning;
```

### 3. Configure application.yml
```yaml
spring:
  datasource:
    url: jdbc:mysql://localhost:3306/online_learning
    username: root
    password: your_password
```

### 4. Run backend
```bash
mvn spring-boot:run
```

### 5. Run frontend
```bash
npm install
npm start
```

---

## API Documentation

- Auth API: /api/auth
- Course API: /api/courses
- Lesson API: /api/lessons
- AI API: /api/ai

Swagger UI:
http://localhost:8080/swagger-ui.html

---

## Security

- JWT-based authentication
- Role-based authorization (STUDENT, INSTRUCTOR, ADMIN)

---

## AI Integration

The AI assistant is implemented as a separate Python service.
The backend communicates with the AI service via REST API.

---

## Future Improvements

- Video streaming optimization
- Recommendation system
- Certificate generation
- Mobile application

---

## Author

- Nguyen Minh
- Educational project
