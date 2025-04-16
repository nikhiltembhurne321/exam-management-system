# Exam Management System

## 📚 Project Name:
**Exam Management System for Teachers**

## 📝 Description:
The Exam Management System is a full-featured web application designed to simplify exam-related tasks for teachers in schools, colleges, and institutions. It allows teachers to upload question papers, view and update results, manage attendance, and handle timetables through a user-friendly dashboard.

## 🚀 Features:
- 🔐 Secure Login/Signup for Teachers
- 🧑‍🏫 Teacher Dashboard with quick navigation
- 📤 Upload Question Papers (PDF/doc files)
- 📊 View and Update Student Results
- ✅ Check and Manage Attendance
- 🗓️ Manage Timetables
- ➕ Create New Timetable (Subject Name, Date, Time)
- ⚡ SweetAlert2 Integration for Alerts
- 💾 Local Storage used for Login Credentials (temporary, can be extended)

## 🛠️ Technologies Used:
### Frontend:
- HTML5  
- CSS3  
- JavaScript  
- SweetAlert2

### Backend:
- Spring Boot (Java)  
- MySQL Database  

## 📦 How to Run

### 🖥️ Prerequisites:
- Java 11 or above
- Spring Boot
- MySQL
- Code Editor (VS Code / Eclipse / IntelliJ)

---

### 🔧 Backend Setup (Spring Boot):
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/exam-management-system.git
   cd exam-management-system
Import project in your IDE (like Eclipse or IntelliJ).

Configure application.properties in src/main/resources:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/exam_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
Run the project using:

bash
Copy
Edit
mvn spring-boot:run
💻 Frontend Setup:
Open index.html in a browser or use Live Server in VS Code.

Use the toolbar to:

Upload question papers

View results

Check attendance

Manage or create timetables



