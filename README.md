# Job Portal Web Application

A full-stack web application connecting job seekers with employers.  
Built with Spring Boot 3, Thymeleaf, and modern Java technologies.


---

## ✨ Features

### 🎯 Job Seeker Features
- Browse and search for jobs using filters (location, job type, date posted)
- Apply to jobs and save favorites
- Manage personal profiles with resume/CV upload
- Track job application history

### 🏢 Recruiter Features
- Create, edit, and manage job postings
- View candidate applications
- Manage company profiles including logo/photo uploads
- Track posted jobs and applicants

---

## 🛠 Technologies Used

| Layer | Stack |
|------|------|
| Backend | Java 17, Spring Boot 3, Spring Security, Spring Data JPA, Hibernate ORM |
| Database | MySQL 8 |
| Frontend | Thymeleaf templates, Bootstrap 5 |
| Tools | Maven, File Upload Handling, ModelMapper |

---

## 🚀 Controllers Overview

| Controller | Main Responsibilities | Key Endpoints |
|------------|------------------------|---------------|
| `HomeController` | Home page routing | `/` → index |
| `JobPostActivityController` | Job post management | `/dashboard/`, `/dashboard/add`, `/global-search/` |
| `JobSeekerApplyController` | Job applications | `/job-details-apply/{id}`, POST apply |
| `JobSeekerProfileController` | Profile management | `/job-seeker-profile/`, file upload/download |
| `JobSeekerSaveController` | Saved jobs management | `/job-details/save/{id}`, `/saved-jobs/` |
| `RecruiterProfileController` | Recruiter profiles | `/recruiter-profile/`, profile photo upload |
| `UsersController` | Authentication and user management | `/register`, `/login`, `/logout` |

