# Virtual Classroom System

A full-stack web application designed to facilitate remote learning by allowing teachers to upload recorded lectures and assignments, and enabling students to access content and submit work in a structured, secure environment.

---


## 📖 Abstract

The Virtual Classroom System is a web-based learning platform that supports recorded content delivery. It enables teachers to share materials and assignments while allowing students to view classes, submit tasks, and monitor their learning. The system is built with modern web technologies ensuring scalability, security, and ease of use.

---

## 🎯 Objectives

- Develop a virtual classroom focused on recorded class delivery.
- Allow admin-controlled teacher registration.
- Enable self-registration for students.
- Provide functionality for assignment submission and tracking.

---

## 🛠️ Tech Stack

| Layer         | Technology            |
|---------------|------------------------|
| **Frontend**  | React.js              |
| **Backend**   | Node.js + Express.js  |
| **Database**  | MongoDB               |
| **Storage**   | Google Drive (video links) |
| **Auth**      | Role-based login (Teacher/Student) |

---

## 🧱 System Architecture

### 👤 Roles:
- **Admin:** Registers teachers manually.
- **Teacher:** Uploads video links, posts assignments.
- **Student:** Registers, views videos, submits assignments.

### 📁 Database Collections:
- `teachers` (in `Virtual` database)
- `students` (in `Virtual` database)
- `videos` and `assignments` per course/module

---

## 📦 Modules

### 1. User Authentication
- Secure login based on role
- Password hashing and validation

### 2. Video Management
- Teachers upload and organize Google Drive links
- Sorted by course/module

### 3. Assignment Handling
- Teachers create and assign tasks
- Students submit file uploads as responses

### 4. Dashboards
- Teacher and student dashboards
- Summary of recent classes, submissions, and alerts

---

## 🌟 Key Features

- 🟢 Flexible recorded class model
- 🔐 Role-based access and login
- 📤 Assignment upload & submission flow
- 📁 MongoDB-backed data structure
- ⚙️ RESTful API using Express.js
- 🧑‍🎓 Real-time student registration
- ✨ Clean React UI with separate views

---

## 🔮 Future Enhancements

- Push/email notifications for updates
- Dashboard analytics for engagement
- Advanced filtering and UI improvements
- Profile customization for all users
- Integration with cloud services (e.g., AWS, Firebase Storage)

---

## ✅ Conclusion

The Virtual Classroom System offers a scalable, secure, and user-friendly platform for recorded content delivery and remote assignment management. It creates a bridge between educators and learners and forms a foundation for more advanced features in the academic technology landscape.

---
