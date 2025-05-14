# Spring Boot User Management Demo

## 📌 Overview
A beginner-friendly Spring Boot project demonstrating user management with MVC architecture, dependency injection, annotations, in-memory storage, and unit testing.

## 🎯 Key Features
- MVC layered structure: Model, Repository, Service
- In-memory user storage via `FakeRepo`
- Service logic with DI
- Unit tests with JUnit 5
- Clean, modular, testable code

## 📁 Structure
spring-boot-user-demo/
├── model/User.java
├── repo/FakeRepoInterface.java / FakeRepo.java
├── service/UserService.java / UserServiceImpl.java
├── DemoApplication.java
└── test/UserServiceTests.java

bash
Copy
Edit

## ⚙️ Tech Stack
- Java 17  
- Spring Boot  
- JUnit 5

## ▶️ Run the App
```bash
git clone <repo-url>
cd spring-boot-user-demo
./gradlew bootRun
🧪 Run Tests
bash
Copy
Edit
./gradlew test
📦 Deliverables Summary
File/Class	Purpose
User.java	Model: id, name, surname
FakeRepo	In-memory data storage
UserServiceImpl.java	Business logic with DI
UserServiceTests.java	Unit testing with JUnit 5

🔀 Git Standards
Use feat, fix, test in commit messages

Branches: main, develop, feature/*

🚀 Conclusion
Great for learning Spring Boot basics, clean coding, testing, and version control best practices.
