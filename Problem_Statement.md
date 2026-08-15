# Problem Statement
## 1. Title
Blood Donation Platform with Emergency Platform
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
1. User - Stores user account and role details
2. Donor Profile - Stores Donor blood group and availability
3. Blood Request - Stores Emergency blood requests
4. Match - Stores donor - request matching details
5. Donation - Stores completed donation records
6. Notification - Stores Notification details
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
Database: PostggreSQL
API Documentation: FastAPI Swagger/ OpenAPI
Testing: Pytest
CI/CD: Github Actions 
