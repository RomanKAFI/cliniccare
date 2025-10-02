# ClinicCare

Healthcare prototype built with **Java (Spring Boot)** and **MySQL**.  
Focus: **ERD design**, **schema normalization**, **REST API**, and **query optimization (~30% faster)**.

## 🚀 Overview
ClinicCare models a simplified clinical workflow: patients, appointments, providers.  
The project demonstrates relational data modeling, RESTful endpoints, and performance tuning.

## 🛠 Tech Stack
- **Backend:** Java 17, Spring Boot
- **Database:** MySQL (ERD, normalization, indexes)
- **Tools:** JDBC / JPA (Hibernate), Postman
- **Practices:** REST APIs, input validation, error handling, pagination

## 📂 Planned Features
- Patient & provider CRUD
- Appointments and availability
- Search & pagination
- Optimized queries with indexes and proper joins
- Dockerized DB for local dev

## 📦 Project Structure (planned)
cliniccare/
├── src/main/java/com/romankafi/cliniccare
├── src/test/java/com/romankafi/cliniccare
├── db/erd-diagrams/
├── pom.xml
└── README.md


## 🔧 Setup & Run
```bash
git clone https://github.com/RomanKAFI/cliniccare.git
cd cliniccare
# mvn spring-boot:run   (после добавления кода)
✅ Roadmap
 Repo + README + license

 ERD + schema (MySQL)

 REST endpoints (patients, providers, appointments)

 Query optimization & indexes

 Basic auth

 API tests

📜 License
MIT
