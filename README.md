# FSD-project
# Fresherlancer – Job Portal for Fresh Graduates 🎓💼

**Fresherlancer** is a full-stack web application designed to bridge the gap between fresh graduates and job opportunities. It allows candidates to register, showcase their education, experience, and skills, and apply to jobs posted by recruiters or agencies. The platform also enables recruiters and admins to post and manage job listings.

## 🚀 Features

- 🔐 Role-based authentication system (Admin, Candidate, Agency)
- 📋 Candidate profile management (education, experience, skills)
- 💼 Job posting with required skills, salary range, and status
- 📄 Application tracking system with status updates
- 🧠 JWT-based secure login system
- 🧾 API documentation with Swagger UI
- 📱 Responsive UI built with Angular and PrimeNG

## 🛠 Technology Stack

### Backend
- Java 21
- Spring Boot 3.4.4
- Spring Security (JWT)
- Spring Data JPA
- Swagger (springdoc-openapi)
- Maven

### Frontend
- Angular 17
- TypeScript
- PrimeNG & PrimeFlex
- Angular Reactive Forms
- Angular Universal (SSR)

### Database
- MySQL 8+
- Structured with normalized tables and foreign key constraints


## 📂 Project Structure

fresherlancer/
├── fresherlancer-backend/                # Spring Boot Backend
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/fresherlancer/   # Java source code
│   │   │   │   ├── controller/           # REST controllers
│   │   │   │   ├── dto/                  # Data Transfer Objects
│   │   │   │   ├── entity/               # JPA entities
│   │   │   │   ├── repository/           # JPA repositories
│   │   │   │   ├── service/              # Service layer
│   │   │   │   └── security/             # JWT & Spring Security config
│   │   │   └── resources/
│   │   │       ├── application.properties
│   │   │       └── schema.sql            # Optional DB schema
│   ├── pom.xml                           # Maven config file
│   ├── mvnw / mvnw.cmd                   # Maven wrapper
│   └── HELP.md                           # Spring Boot starter help

├── fresherlancer-frontend/               # Angular Frontend
│   ├── src/
│   │   ├── app/
│   │   │   ├── components/               # UI components
│   │   │   ├── services/                 # API services
│   │   │   ├── models/                   # Interfaces/Models
│   │   │   ├── pages/                    # Page-level views
│   │   │   └── app.module.ts             # App module config
│   │   ├── assets/
│   │   ├── environments/
│   │   │   ├── environment.ts
│   │   │   └── environment.prod.ts
│   │   └── index.html
│   ├── angular.json                      # Angular CLI config
│   ├── package.json                      # Node package dependencies
│   └── tsconfig.json                     # TypeScript config

├── sql-dump.sql                          # MySQL schema and demo data
├── README.md                             # Project documentation (this file)
└── .gitignore

🧪 Testing the API
Use Postman or access the Swagger UI:
http://localhost:8080/swagger-ui.html

## 🧠 Purpose
This project was developed as part of a 3-month Java Full Stack Development course at Symbiosis Institute. It helped reinforce skills in full-stack architecture, secure API design, relational databases, and user-centered UI development.

## 🙌 Acknowledgments
Symbiosis Institute – Java Full Stack Program
PrimeNG for rich UI components
Spring Boot and Angular communities for extensive documentation and support


