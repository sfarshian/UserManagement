UserManagement 🚀👥

A robust user management backend built with Java & Spring Boot, featuring modern authentication, structured logging, and clean architecture.
📌 Overview

UserManagement is a powerful backend application that handles user registration, authentication, and management with a strong focus on security and maintainability. It supports:

    🔐 Google OAuth2 login

    🔑 JWT-based authentication

    🛠️ Aspect-Oriented Programming (AOP)

    📝 Custom annotations & exception handling

    🧩 Modular cross-cutting concerns

    ⚙️ Full CRUD functionality

🛠️ Technologies & Features

    💻 Java & Spring Boot

    🌍 Google OAuth2 for secure social login

    🔐 JWT (JSON Web Tokens) for stateless auth

    🗂️ SLF4J Logging for consistent logs

    🚨 Custom Exceptions & Controller Advice for clean error handling

    🔄 AOP for handling cross-cutting concerns

    ✨ Custom Annotations to simplify validations and logic

🚀 Features

    👤 Google OAuth2 login integration

    🔑 JWT token-based authentication & authorization

    🧾 Structured logging with SLF4J

    ⚡ Centralized exception handling with custom exceptions

    🎯 Modular cross-cutting concerns via AOP aspects

    🛠️ RESTful API endpoints for user CRUD operations

📦 Getting Started
Prerequisites

    ☕ Java 8+

    🧩 Maven

    🔑 Google OAuth2 credentials (client ID & secret)

Installation

    Clone this repo:

git clone https://github.com/sfarshian/UserManagement.git
cd UserManagement

Configure your Google OAuth2 credentials in application.properties or application.yml.

Build the project:

mvn clean install

Run the app:

    mvn spring-boot:run

    Access at http://localhost:8080 🎉
