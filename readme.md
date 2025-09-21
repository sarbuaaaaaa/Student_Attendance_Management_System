# 📘 Student Attendance Management System

A full-stack web application built using **Angular** (frontend) and **Spring Boot** (backend) to manage student attendance efficiently.  
It supports both **manual attendance marking** and **QR code-based attendance** for real-time updates.

---

## 🚀 Features

- **Student Management**

  - Add, update, and delete student records.
  - View student details with attendance history.

- **Attendance Management**

  - **Manual Mode**: Teachers can mark attendance manually.
  - **QR Code Mode**: Students scan a QR code to mark attendance automatically.

- **Real-Time Updates**

  - Attendance data is updated instantly.
  - Dashboard for quick insights.

- **Authentication & Authorization**

  - Secure login for admin/teachers (can be implemented with JWT).
  - Role-based access control.

- **Reports & Analytics**
  - Generate attendance reports.
  - Export data for academic use.

---

## 🛠️ Tech Stack

### Backend

- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database (or MySQL/PostgreSQL)
- REST APIs

### Frontend

- Angular 14+
- TypeScript
- HTML/CSS
- Bootstrap
- Optional: QR code scanner libraries (`ngx-scanner`, `html5-qrcode`)

---

## ⚡ Installation

### Backend

```bash
cd backend
mvn clean install
mvn spring-boot:run
```
