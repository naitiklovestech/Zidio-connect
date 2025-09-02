# Software Requirements Specification (SRS)
## Project: Zidio Connect
**Prepared for:** Java Full Stack Interns  
**Prepared by:** Team Zidio Development

---

## 1. Introduction

### 1.1 Purpose
Zidio Connect is a web-based internship and job management portal designed to bridge the gap between students and recruiters. The system allows companies to post internships/jobs, students to apply and manage applications, and admins to oversee the entire platform with moderation and analytics.

### 1.2 Scope
The platform provides:
- Internship and job posting capabilities for recruiters.
- Student dashboards for profile creation, resume uploads, application management, and tracking.
- Recruiter dashboards for managing job listings and applications.
- Admin control for user management, moderation, and analytics.
- Optional integration with AI APIs for smart insights from uploaded data.

### 1.3 Definitions, Acronyms, and Abbreviations
- **UI** – User Interface
- **API** – Application Programming Interface
- **ER Diagram** – Entity Relationship Diagram
- **DB** – Database

### 1.4 References
- Project Documentation (Zidio Connect Project Brief)
- www.zidio.in

---

## 2. Overall Description

### 2.1 Product Perspective
Zidio Connect is an independent web platform built on a full-stack architecture. It integrates frontend, backend, and database layers with role-based authentication. Optional external APIs (AI, email, file storage) may be used.

### 2.2 Product Functions
- **Authentication Module**: Role-based login and registration (Student, Recruiter, Admin).
- **Student Dashboard**: Profile management, resume upload, view/apply to opportunities, application tracking.
- **Recruiter Dashboard**: Post/manage listings, view applicants, shortlist/reject candidates.
- **Admin Panel**: User approval/blocking, content moderation, analytics and reporting.
- **Job/Internship Management**: Listing, searching, filtering, bookmarking, notifications.
- **Optional Add-ons**: Email notifications, chat/messaging system, resume builder, analytics dashboard.

### 2.3 User Classes and Characteristics
- **Students**: Apply to internships/jobs, track applications.
- **Recruiters**: Post/manage job opportunities, review applicants.
- **Admins**: Moderate content, manage users, generate reports.

### 2.4 Operating Environment
- **Frontend**: HTML, CSS, JavaScript, React.js or JSP
- **Backend**: Java, Spring Boot
- **Database**: MySQL
- **Tools**: Git/GitHub, Postman, Cloudinary (optional for file storage)
- **Deployment**: Cloud/local server

### 2.5 Design and Implementation Constraints
- Role-based authentication required.
- Must support Excel file (.xls, .xlsx) uploads for data analysis (for analytics features).
- Follow Agile methodology with sprint cycles.
- Git for version control and collaborative development.

---

## 3. System Features

### 3.1 Authentication Module
- Registration with role selection (Student, Recruiter, Admin).
- Secure login and session management.
- Password encryption and recovery.

### 3.2 Student Dashboard
- Profile creation and management.
- Resume upload and storage.
- Browse, apply, and track job/internship applications.
- Notification system for updates.

### 3.3 Recruiter Dashboard
- Post job/internship listings.
- View applicants and application details.
- Shortlist or reject candidates.
- Receive notifications on applications.

### 3.4 Admin Panel
- User management (approve, block, or remove accounts).
- Content moderation.
- System usage analytics and reporting.

### 3.5 Job/Internship Management
- Search and filter opportunities by category, location, etc.
- Bookmark/save listings.
- Notification alerts for new postings.

### 3.6 Optional Add-ons
- Email notification integration.
- Chat/messaging system between students and recruiters.
- Resume builder tool for students.
- Advanced analytics dashboard for admins.

---

## 4. Database Requirements

### 4.1 Database Design
- MySQL-based relational database.
- ER Diagram to define relationships among users, roles, job listings, applications, and resumes.

### 4.2 Data Storage
- User profiles, resumes, and application history.
- Job postings and recruiter details.
- System logs and analytics data.

---

## 5. Non-Functional Requirements

### 5.1 Performance
- The system should handle concurrent access by multiple users.
- Response time for dashboard actions must be under 2 seconds.

### 5.2 Security
- Role-based access control.
- Encrypted password storage.
- Secure API endpoints with authentication tokens.

### 5.3 Reliability & Availability
- System uptime target: 99%.
- Automated backups of database.

### 5.4 Usability
- Intuitive UI/UX with responsive design.
- Accessible on desktops, tablets, and mobile devices.

---

## 6. Project Milestones

1. Requirement Gathering & Analysis
2. Database Design & ER Diagram
3. Backend API Development
4. Frontend Integration
5. Testing & Debugging
6. Deployment & Documentation

---

## 7. Deliverables

- Source Code (Frontend + Backend)
- Database Schema & ER Diagram
- Deployment Guide
- User Manual
- Final Project Report with screenshots

---

## 8. Evaluation Criteria

- Functionality and Features
- Code Quality and Best Practices
- UI/UX Design
- Team Collaboration
- Documentation Completeness

---

## 9. Team Roles

- **Frontend Developer** – Build user interfaces and dashboards.
- **Backend Developer** – Implement APIs and business logic.
- **Database Manager** – Design and manage schema.
- **QA & Testing** – Conduct testing and ensure quality.

---

## 10. Timeline

### 3-Month Plan (Long-Term)
- Focus: Multiple modules including Admin Panel and Analytics.
- Deliverable: Robust, deployable version with advanced features.

---

## 11. Coordination Strategy

- Agile sprint cycles of 1–2 weeks.
- Independent work per batch duration (1, 2, or 3 months).
- Version control via Git.
- Use of collaborative tools (Trello/Jira).
- Regular stand-ups and reviews.

---

## 12. Contact
**Project Mentor:** Samridhi Kumar  
**Email:** hr@zidio.in  
**Website:** [www.zidio.in](http://www.zidio.in)

---
