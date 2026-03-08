![Java](https://img.shields.io/badge/Java-Backend-red)
![SpringBoot](https://img.shields.io/badge/SpringBoot-Framework-green)
![JSP](https://img.shields.io/badge/JSP-Frontend-orange)
![MySQL](https://img.shields.io/badge/MySQL-Database-blue)
![AWS](https://img.shields.io/badge/AWS-Deployment-yellow)

# Aadarsh Coaching Automation System

Aadarsh Coaching Automation System is a **full-stack web application** developed to automate the daily operations of a coaching institute with **30+ years of legacy**.

This project was developed as a **sponsored real-world project** to digitize admission processes, administrative work, and institute information management.

The platform provides an efficient system for managing **student registrations, admission records, course details, and administrative operations** through a secure web interface.

---

# 🚀 Project Features

## 🎓 Student Admission System

Students can easily register and submit admission requests through the website.

Features:

• Online student registration
• Admission form submission
• Secure storage of student details
• Printable admission forms

All admission data is automatically stored in the **database** and accessible to administrators.

---

# 👨‍💼 Admin Dashboard

Admins can manage the entire system through a dedicated dashboard.

Features:

• Admin login authentication
• View all admission requests
• Manage student records
• Edit or update admission details
• Generate printable admission forms

This reduces manual paperwork and improves administrative efficiency.

---

# 🏫 Institute Information Portal

The system also provides detailed information about the coaching institute.

Sections include:

• About the Institute
• Founder Details
• Institute Overview
• Contact Information

These sections help students and parents learn more about the institute.

---

# 📸 Activities & Gallery

The platform includes visual sections to showcase institute activities.

Modules include:

📌 **Activities Section** – Displays extracurricular activities with images.

📌 **Memory Section** – Highlights important moments and milestones from the institute’s **30-year journey**.

📌 **Gallery** – Shows images of events and institute activities.

---

# 🔐 Secure Authentication

The system uses **Spring Security with BCrypt password hashing** for secure authentication.

Features:

• Secure login system
• Password encryption
• Admin access protection

---

# 🛠 Tech Stack

## Backend

• Java
• Spring Boot
• Spring MVC
• Spring Data JPA
• Spring Security

## Frontend

• JSP
• HTML
• CSS
• JavaScript

## Database

• MySQL
• Hibernate (JPA)

## Deployment

• AWS Cloud

## Build Tool

• Maven

---

# 🏗 Project Architecture

The application follows **MVC Architecture**.

Controller → Handles HTTP requests
Service → Business logic layer
Repository → Database operations
Model → Entity classes
View → JSP pages

---

# 📂 Project Structure

```
src/main/java/com/example/aadarshproject

controller
service
repository
model
config

src/main/resources

application.properties

src/main/webapp/WEB-INF/jsp

HomePage.jsp
Studentlogin.jsp
AdminLogin.jsp
admindash.jsp
register.jsp
editAdmission.jsp
printAdmission.jsp
Gallery.jsp
Activity.jsp
AboutInstitute.jsp
Contact.jsp
```

---

# ⚙️ Application Configuration

Important settings from **application.properties**:

```
spring.application.name=aadarshproject
server.port=8086

spring.datasource.url=jdbc:mysql://localhost:3306/aadarshproject
spring.datasource.username=root
spring.datasource.password=root

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

# 📸 Screenshots

Add screenshots of:

• Home Page
<img width="1347" height="621" alt="image" src="https://github.com/user-attachments/assets/b5b69644-5ea0-42d0-9573-89a4b1ea7c4a" />
<img width="1277" height="616" alt="image" src="https://github.com/user-attachments/assets/527eb8d2-ee3e-45fc-8f7d-f42c715ae792" />

• Student Registration Page
<img width="1325" height="636" alt="image" src="https://github.com/user-attachments/assets/b69d044f-d7df-4ddb-bc16-7511f2622a12" />
<img width="729" height="535" alt="image" src="https://github.com/user-attachments/assets/a05ed219-f561-453d-9de5-78b5e2628bab" />


• Admission Form
<img width="500" height="609" alt="image" src="https://github.com/user-attachments/assets/15661322-fed6-4254-b497-aa311f8c19e4" />

• Admin Dashboard
<img width="614" height="530" alt="image" src="https://github.com/user-attachments/assets/4ccae5e9-e19c-4543-817a-4d7a0c7cb917" />
<img width="1359" height="580" alt="image" src="https://github.com/user-attachments/assets/9602e645-3ad8-4354-b81d-3ff0ad30011f" />
<img width="1338" height="625" alt="image" src="https://github.com/user-attachments/assets/adeab8e8-f452-4a0b-950e-4fd0912960e5" />

• Activities Page
<img width="1182" height="662" alt="image" src="https://github.com/user-attachments/assets/cad552b7-c3af-436c-8420-33c00583a4d5" />
<img width="1028" height="601" alt="image" src="https://github.com/user-attachments/assets/76b7abfe-1963-4028-89dc-d43ad172c94b" />
<img width="1048" height="612" alt="image" src="https://github.com/user-attachments/assets/7eb9d4c5-2587-406f-9e8c-e7f0fe690976" />

• Gallery Page
<img width="1051" height="555" alt="image" src="https://github.com/user-attachments/assets/3e23bd0d-0a0a-4972-94ed-8b5b9148ea46" />

---

# ▶️ How to Run the Project

### 1 Clone Repository

```
git clone https://github.com/Manish-Sawant30/aadarshproject.git
```

---

### 2 Open Project

Open the project in:

• IntelliJ IDEA
• Eclipse
• VS Code

---

### 3 Setup Database

Create MySQL database:

```
aadarshproject
```

---

### 4 Configure Database

Update credentials in:

```
application.properties
```

Example:

```
spring.datasource.username=root
spring.datasource.password=root
```

---

### 5 Run Application

Run the main class:

```
AadarshprojectApplication.java
```

---

### 6 Open Browser

```
http://localhost:8086
```

---

# 🎯 Learning Outcomes

This project helped improve understanding of:

• Requirement analysis from real clients
• Full-stack development workflow
• Backend-frontend integration
• Database design and management
• Cloud deployment using AWS

---

# 👨‍💻 Developer

**Manish Sawant**

Diploma in Computer Technology
Java Full Stack Developer

GitHub
https://github.com/Manish-Sawant30
