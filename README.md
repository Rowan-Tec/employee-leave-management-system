# Employee Leave Management System

Full-stack application built with **Java Spring Boot** (Backend) + **React.js** (Frontend).

## Project Structure
├── backend/          ← Spring Boot + JPA + JWT + MySQL
├── frontend/         ← React.js + Axios + Responsive UI
├── .gitignore
└── README.md
text### Features
- JWT Authentication (Admin + Employee roles)
- Leave Application & Approval System
- Public Holidays API Integration
- Responsive Dashboard

**Tech Stack**
- Backend: Spring Boot 3, Spring Security, JPA/Hibernate, MySQL
- Frontend: React.js, Axios
- Others: Lombok, Validation, Maven

---

5. **Improve .gitignore** (if it exists, edit it; otherwise create it):

   - Click **"Add file"** → **"Create new file"**
   - Name the file: `.gitignore`
   - Paste the following content:

```gitignore
# Backend
backend/target/
backend/.mvn/
backend/.idea/
backend/*.iml

# Frontend
frontend/node_modules/
frontend/.env
frontend/build/
frontend/.next/
frontend/dist/

# General
.DS_Store
*.log
.env
*.env.local
*.env.development.local
*.env.test.local
*.env.production.local
