# 🔐 User Authentication System

A secure and scalable user authentication system built with Spring Boot and JWT. It supports user registration, login, token-based authentication, and role-based access control. Designed for integration into full-stack applications and microservices.

## 🚀 Features

- 📝 User registration with validation  
- 🔑 Login with JWT token generation  
- 🔒 Protected routes using token-based access  
- 🛡 Role-based authorization (Admin/User)  
- 🔁 Token refresh and logout (optional)  
- 📦 RESTful API structure

## 🛠 Tech Stack

| Layer       | Technology             |
|-------------|------------------------|
| Backend     | Spring Boot, Spring Security  
| Auth        | JWT (JSON Web Tokens)  
| Database    | PostgreSQL / MySQL / H2  
| Tools       | Postman, Swagger, Maven

## 📦 Installation

### 🔧 Backend Setup

```bash
git clone https://github.com/your-username/auth-system.git
cd auth-system
./mvnw spring-boot:run
