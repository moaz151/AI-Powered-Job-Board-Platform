
# AI-Powered-Job-Board-Platform
## Getting Started

You can explore and try the project using the links below.

### Live Demo

- **Job Office:** https://job-backoffice-production-bsmynx.laravel.cloud/login
  - For administrators and company owners.
- **Job App:** https://job-app-production-ok3wn5.laravel.cloud/
  - For job seekers to browse and apply for jobs.

### Source Code

- **Job Office:** https://github.com/moaz151/job-backoffice
- **Job App:** https://github.com/moaz151/job-app
- **Job Share:** https://github.com/moaz151/job-shared

### How to Use

1. Open **Job App** to browse available job opportunities and apply for jobs.
2. Open **Job Office** to access the management dashboard.
    To Login as Admin use this:
          Email: admin@admin.com
          password: 123123
   To Login as Company Owner use this:
          Email: owner@owner.com
          password: 12341234
4. Log in using the appropriate account to explore the features available for your role.







# Job Board Platform

A job board platform designed to connect job seekers with companies, allowing companies to manage their job postings and applications while providing administrators with complete control and insights into the platform.

The project consists of **three main components**:

## 1. Job Office (`job-office`)

The management panel for **Administrators and Company Owners**.

- **Administrators:** Can manage the platform and access overall statistics and analytics.
- **Company Owners:** Can manage their company, monitor job applications, and track applicants' progress.

Users can log in to access features and information based on their roles and permissions.

## 2. Job App (`job-app`)

The main application for **Job Seekers**.

Through this application, job seekers can:

- Browse and explore available job opportunities.
- Apply for jobs.
- Track and manage their submitted applications.
- Follow the status of their job applications.

## 3. Job Share (`job-share`)

A custom Laravel package developed to share common code and functionality between `job-office` and `job-app`.

It acts as a centralized location for shared Eloquent Models and other common components, allowing both applications to interact with the same underlying data structure.

**Main purpose:**
- Avoid code duplication.
- Centralize shared models.
- Maintain consistency between both applications.
- Simplify development and deployment.

---

## Project Architecture

The project follows a modular architecture where each application has a separate responsibility:

| Component | Responsibility |
|---|---|
| `job-office` | Administration and company management |
| `job-app` | Job seeker experience |
| `job-share` | Shared models and common functionality |

## Tech Stack

- **Backend:** PHP / Laravel
- **Database:** MySQL
- **Architecture:** Multiple Laravel Applications with a Shared Laravel Package

---

**Project Goal:** Build a maintainable and scalable job board platform with separated user experiences and reusable shared components.
