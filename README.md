# CAB-SERVICE
This Cab Booking Application is a backend system built using Microservices architecture with Spring Boot. It allows users to book cabs, make payments, receive notifications, and manage their profiles in a secure and modular environment. Each microservice is independently deployable and communicates via REST APIs, ensuring scalability and maintainability.

🔧 Tech Stack
Java, Spring Boot, Maven
Spring Security with JWT for authentication and authorization
Spring Cloud Gateway, Eureka Server for API routing and service discovery
MySQL for persistent storage
Spring Data JPA, Hibernate f
Lombok for boilerplate reduction
Postman for API testing
Swagger

📦 Microservices Overview
User Service: Handles user registration, login, and role-based access (Admin, Rider).
Cab Service: Manages cab details, driver profiles, cab availability, and location tracking.
Booking Service: Handles ride booking, ride history, and booking status.
Payment Service: Manages fare calculation, payment processing, and transaction history.
Notification Service: Sends email/SMS notifications for booking updates, payment status, and alerts.
API Gateway: Routes client requests to respective services.
Eureka Discovery Server: Enables dynamic service registration and lookup.

🔐 Security & Access Control
Implemented using Spring Security with JWT-based authentication. Users are authenticated through secure login, and Role-Based Access Control (RBAC) restricts endpoint access. Passwords are encrypted using BCrypt. The API Gateway validates tokens before forwarding requests.

📬 REST API & Testing
All services expose RESTful APIs following standard HTTP methods and status codes. APIs are tested using Postman, ensuring reliability and proper error handling across services.
