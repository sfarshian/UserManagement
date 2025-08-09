# UserManagement 🚀👥

A robust user management backend built with Java & Spring Boot, featuring modern authentication, structured logging, and clean architecture.

## 📌 Overview

**UserManagement** is a powerful backend application that handles user registration, authentication, and management with a strong focus on security and maintainability. It supports:

* 🔐 Google OAuth2 login
* 🔑 JWT-based authentication
* 🛠️ Aspect-Oriented Programming (AOP)
* 📝 Custom annotations & exception handling
* 🧩 Modular cross-cutting concerns
* ⚙️ Full CRUD functionality

## 🛠️ Technologies & Features

* 💻 **Java & Spring Boot**
* 🌍 **Google OAuth2** for secure social login
* 🔐 **JWT (JSON Web Tokens)** for stateless auth
* 🗂️ **SLF4J Logging** for consistent logs
* 🚨 **Custom Exceptions & Controller Advice** for clean error handling
* 🔄 **AOP** for handling cross-cutting concerns
* ✨ **Custom Annotations** to simplify validations and logic

## 🚀 Features

* 👤 Google OAuth2 login integration
* 🔑 JWT token-based authentication & authorization
* 🧾 Structured logging with SLF4J
* ⚡ Centralized exception handling with custom exceptions
* 🎯 Modular cross-cutting concerns via AOP aspects
* 🛠️ RESTful API endpoints for user CRUD operations

## 📦 Getting Started

### Prerequisites

* ☕ Java 8+
* 🧩 Maven
* 🔑 Google OAuth2 credentials (client ID & secret)

### Installation

1. Clone this repo:

   ```bash
   git clone https://github.com/sfarshian/UserManagement.git
   cd UserManagement
   ```

2. Configure your Google OAuth2 credentials in `application.properties` or `application.yml`.

3. Build the project:

   ```bash
   mvn clean install
   ```

4. Run the app:

   ```bash
   mvn spring-boot:run
   ```

5. Access at [http://localhost:8080](http://localhost:8080) 🎉
