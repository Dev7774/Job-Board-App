# 🧳 JobBoard API – Backend with Django & PostgreSQL

This is a backend-only Django application for a Job Board platform. It includes user authentication, job listings, and application management using Django’s built-in admin and PostgreSQL as the database.

## 📌 Features

- Employers:
  - Post, update, and delete jobs
  - View received applications
- Job Seekers:
  - View job listings
  - Apply for jobs with resume upload
- Django Admin for full backend management
- PostgreSQL for production-ready database setup

---

## ⚙️ Tech Stack

- **Backend:** Django (Python 3.10+)
- **Database:** PostgreSQL
- **Authentication:** Django built-in auth system
- **File Handling:** Resume upload via Django's media storage

---

## 📂 Project Structure

jobboard/
├── accounts/ # User model and auth
├── jobs/ # Jobs and applications
├── media/ # Uploaded resumes
├── jobboard/ # Main settings
├── db.sqlite3 # (Replaced by PostgreSQL)
└── manage.py



---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/dev7774/jobboard-backend.git
cd jobboard-backend
