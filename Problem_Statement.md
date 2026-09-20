# Problem Statement
## 1. Title
Blood Donation Platform with Emergency Patterns Matching
## 2. Domain
Health Technologies
## 3. Who is the user?
### Donor
A registered user who provides blood group and availability
### Receiver
A user who creates an emergency blood request
### Admin 
Manages users, donors, blood requests, and platform activities
## 4. What problem are we solving?
During blood emergencies, patients may struggle to find suitable donors quickly.
This platform connects receivers with available donors based on blood group compatibility and availability.
It helps reduce the time required to find potential donors.
## 5. Proposed Solution
The System provides secure signup and login, donor registration, emergency blood requests, and automatic donor matching.
It also allows admins to manage users and requests and maintains donation and notification records.
## 6. Core Entities/Database Tables
DONOR – Stores information about people who donate blood, including their blood group, age, contact details, and donation history.
HOSPITAL – Stores hospital details such as hospital name, address, city, and contact number.
PATIENT – Stores patient information, including required blood group, contact details, emergency level, and associated hospital.
EMERGENCY_REQUEST – Records emergency blood requests made for patients, including blood group required, quantity, and request status.
DONATION – Stores details of blood donations, including donor, blood bank, blood group, donation date, and quantity.
BLOOD BANK – Stores information about blood banks, including name, location, contact details, capacity, and stored blood donations.
## 7. Success Criteria
The system is successful when users can register and log in securely.
donors can maintain their availability.
receivers can create emergency requests.
The System must identify suitable donors and complete the main flows from frontend to backend 
and database.
## 8. Out of Scope
Real-time blood-bank inventory integration
Medical Diagnosis or advice
Real-time location tracking  
## 10. Chosen Track
Python - FastAPI
## Planned Technology Stack 
Frontend: React.js
Backend: FastAPI,Python
Authentication: JWT
ORM: SQLAlchemy
Database: SQL Lite
API Documentation: FastAPI Swagger/ OpenAPI
Testing: Pytest
CI/CD: Github Actions 
