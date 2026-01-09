# Online Learning Platform

## 1. Purpose

This project is an online learning platform designed to support online education.
The system helps students learn through structured courses and provides instructors
with tools to manage learning content.
An AI assistant is integrated to support users and improve learning efficiency.

---

## 2. Technologies Used

### Backend
- Java 21
- Spring Boot
- Spring Data JPA
- Spring Security (JWT)
- MySQL

### Frontend
- React
- Axios
- React Router

### AI Assistant
- Python
- REST API integration

---

## 3. How to Use the Web Application

### 3.1 User Registration and Login
- Users can register a new account or log in using an existing account.
- Authentication is handled securely using JWT.

### 3.2 Course Enrollment
- Students can browse available courses.
- Students can enroll in courses and access course content after enrollment.

### 3.3 Learning Process
- Courses are organized into modules, sections, and lessons.
- Lessons can be video-based or text-based.
- Students can track their learning progress for each lesson.

### 3.4 Assignments
- Students can view assignments associated with lessons.
- Students can submit their assignments online.
- Instructors can review submissions and provide feedback.

### 3.5 Learning Progress Tracking
- The system records learning progress for each lesson.
- Students can monitor their completion status and progress percentage.

### 3.6 AI Assistant
- The AI assistant helps users understand how to use the application.
- The AI provides guidance and explanations for exercises and assignments.
- AI interactions are stored for future reference.

---

## 4. Main Features

### Student
- Register and login
- Enroll in courses
- View lessons
- Submit assignments
- Track learning progress
- Use AI assistant for learning support

### Instructor
- Create and manage courses
- Organize modules, sections, and lessons
- Create assignments
- View student progress

### Administrator
- Manage users
- Manage system data

---

## 5. Project Structure

```text
src
└── main
    ├── java
    │   └── com.example.onlinelearning
    │       ├── constants
    │       ├── controller
    │       ├── service
    │       ├── repository
    │       ├── entity
    │       ├── dto
    │       ├── config
    │       └── OnlineLearningApplication.java
    └── resources
        └── yaml
```

---

## 6. Notes
- This project is for educational purposes only
- Sensitive information (database credentials, secret keys) is not included in this repository
- The system can be extended with more features in the future

