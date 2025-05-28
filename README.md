🔐 Secure RESTful API with JWT Authentication & Role-Based Authorization

This project is a secure backend API built with ASP.NET Core Web API, demonstrating JWT-based authentication and role-based access control (RBAC). It supports user login/registration, generates secure tokens, and restricts API access based on roles such as Admin and User.

🚀 Features
✅ JWT Authentication: Secure user login and token generation using JSON Web Tokens.

🔐 Role-Based Authorization: Fine-grained access control based on user roles.

🛠️ Entity Framework Core: Code First approach with Migrations and SQL Server 2018 integration.

📄 Swagger UI: Interactive API documentation for testing and exploring endpoints.

🧪 Postman Tested: All endpoints tested and verified via Postman.

🔍 Token Verification: JWT tokens validated using tools like jwt.io.

🧱 Clean Architecture: Separation of concerns and scalable design patterns.

🧑‍💻 Tech Stack
ASP.NET Core Web API

C#

Entity Framework Core

SQL Server 2018

JWT (JSON Web Tokens)

Swagger

Postman

Visual Studio 2022

📂 Key Endpoints (Sample)
POST /api/auth/login – Authenticate and receive JWT token

POST /api/auth/register – Register a new user

GET /api/admin/dashboard – Protected route for Admin role

GET /api/user/profile – Protected route for User role
