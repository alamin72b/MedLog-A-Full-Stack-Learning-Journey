# 💊MedLog — Project Requirements Document

**Project Phase:** Step 1 — Planning & Requirement Analysis  
**Last Updated:** October 2025  
**Maintainer:** [@alamin72b](https://github.com/alamin72b)  

---

## 1. 🧭 Project Overview

**MedLog** is a **personal medical tracking web application** designed to help users securely log, monitor, and visualize their health data — such as medication schedules, doctor visits, and test results.

The project aims to combine simplicity, privacy, and insight, allowing users to take control of their personal health information.  
MedLog also serves as a **learning project** to document a full-stack journey — from planning to deployment — in a transparent, educational way.

---

## 2. 🚨 Problem Statement

People often struggle to manage their health records efficiently.  
They rely on scattered notes, paper prescriptions, or unorganized photos of reports.  
As a result:
- Data becomes hard to access in emergencies.
- Patients forget medications or test schedules.
- There’s no central way to track health trends over time.

**MedLog** solves this by providing a single digital space for recording and analyzing medical data, accessible anytime, anywhere.

---

## 3. 🎯 Goals and Objectives

| Goal ID | Description | Success Criteria |
|----------|--------------|------------------|
| G1 | Create a centralized personal health log | Users can store and view all health data from a single dashboard |
| G2 | Implement secure login and authentication | Only authorized users can access their data |
| G3 | Enable medication reminders and tracking | System can notify users of upcoming doses |
| G4 | Provide basic analytics and trends | Users can visualize health metrics via charts |
| G5 | Build a responsive and accessible UI | Works smoothly on desktop and mobile |

---

## 4. 📦 Project Scope

### In Scope
- User registration, login, and logout  
- CRUD operations for medical logs (appointments, reports, etc.)  
- Medication schedule and reminders  
- Analytics dashboard (charts, insights)  
- Secure data storage  
- REST API with documentation  

### Out of Scope (Future)
- Doctor/patient multi-user system  
- Integration with wearable devices (Fitbit, Apple Health)  
- Voice input or AI suggestions  
- Offline mobile app version  

---

## 5. 👤 Target Users & Personas

| Persona | Description | Pain Points | What MedLog Solves |
|----------|--------------|-------------|--------------------|
| Student/Young Adult | Busy, tech-comfortable user | Forgets doses or follow-ups | Central reminders and quick health notes |
| Working Professional | Juggles work-life-health balance | Scattered health info | Accessible dashboard on the go |
| Elderly User | Needs medication management | Hard to remember doses | Easy-to-use reminders and record view |

---

## 6. ⚙️ Functional Requirements

| ID | Requirement | Description |
|----|--------------|-------------|
| FR-1 | User Authentication | Users can register, log in, and log out securely |
| FR-2 | Profile Management | Users can update personal details and settings |
| FR-3 | Add Medical Records | Users can add appointments, medications, and reports |
| FR-4 | Edit/Delete Records | Users can modify or delete entries |
| FR-5 | Dashboard Overview | Shows summary and charts of user data |
| FR-6 | Reminder System | Sends notifications for medications and appointments |
| FR-7 | Data Security | All sensitive data is encrypted and private |
| FR-8 | API Endpoints | Provide REST API for frontend-backend communication |

---

## 7. 🧱 Non-Functional Requirements

| Category | Requirement |
|-----------|--------------|
| Performance | Dashboard loads within 2 seconds |
| Reliability | System uptime of 99% (local simulated) |
| Usability | Interface should be clear and accessible |
| Security | Passwords hashed, HTTPS enforced |
| Scalability | Backend supports 1000+ records per user |
| Maintainability | Code follows modular structure and clean architecture |

---

## 8. ⚖️ System Constraints

- Using free-tier services (e.g., Render, Supabase, or Vercel)  
- Limited database size or performance on free plan  
- Limited email quota for reminders  
- Learning project timeline (~3 months)

---

## 9. 🧰 Tools & Technology Stack

| Layer | Technology | Purpose |
|--------|-------------|----------|
| Frontend | React + TypeScript | Build the user interface |
| Backend | Node.js (Express) | Handle API and logic |
| Database | PostgreSQL (Supabase) | Store and manage health data |
| Authentication | JWT / Supabase Auth | Secure login and session control |
| Styling | Tailwind CSS + Shadcn UI | Fast, modern, and consistent styling |
| Visualization | Chart.js or Recharts | Display health data trends |
| Dev Tools | Git, ESLint, Prettier | Version control and code quality |
| Deployment | Vercel / Render | Hosting frontend and backend |

---

## 10. ⚠️ Risks and Mitigation

| Risk | Impact | Mitigation |
|-------|---------|-------------|
| API downtime | High | Add retry logic or offline fallback |
| Time constraints | Medium | Prioritize core features first |
| Data loss | High | Frequent backups and validation |
| Security flaws | High | Follow best practices, review dependencies |
| Scope creep | Medium | Stick to “In Scope” list for MVP |

---

## 11. 📊 Success Metrics

| Metric | Target |
|--------|---------|
| User registration and login success | 100% |
| Data retrieval time | < 2 seconds |
| Dashboard load time | < 3 seconds |
| Reminder notifications success rate | > 90% |
| Documentation completeness | 100% by end of phase |

---

## 12. 🛣️ Future Roadmap

| Phase | Focus Area | Description |
|--------|-------------|-------------|
| Step 1 | Planning | Requirement analysis and documentation |
| Step 2 | Design | Wireframes, database schema, API design |
| Step 3 | Development | Build frontend and backend |
| Step 4 | Testing | Write unit and integration tests |
| Step 5 | Deployment | Host and publish project |
| Step 6 | Maintenance | Add improvements and future features |

---

## ✅ Validation Checklist

- [x] Problem and goals clearly defined  
- [x] Functional requirements realistic  
- [x] Tech stack finalized  
- [x] Risk plan ready  
- [x] Document formatted for readability  

---

> _“Plan it right, build it bright.”_  
> — *MedLog Planning Phase, 2025*

---

📎 **Walkthrough Reference:**  
[View the Planning Walkthrough →](../walkthrough/planning.md)
