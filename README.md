# 🦁 WildTour Web Application

A full-stack Java web application developed as part of the **Java Full Stack Development Internship** at **Pentagon Space**. The application provides a user-friendly platform for exploring wildlife tourism destinations, viewing travel packages, and managing tour bookings through an interactive web interface.

## 📌 Project Overview

WildTour is designed to simplify wildlife tourism management by allowing users to browse safari packages, accommodation options, guide services, and travel packages while securely managing bookings through a database-driven system.

The project demonstrates the integration of frontend, backend, and database technologies in a complete Java web application.

---

## ✨ Features

- User Registration and Login
- Browse Wildlife Safari Packages
- Explore Tour Packages
- Accommodation Booking
- Guide Service Information
- Photography & Wildlife Sightings
- Tour Booking Management
- View Booked Trips
- Contact Page
- Responsive User Interface
- MySQL Database Integration

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Java
- JSP
- Servlets
- JDBC

### Database
- MySQL

### Development Tools
- Eclipse IDE
- Apache Tomcat
- MySQL Workbench
- Git
- GitHub

---

## 📂 Project Structure

```
WildTour/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   ├── webapp/
│
├── pom.xml
├── wildlife.sql
├── README.md
```

---

## 🗄 Database Setup

1. Open MySQL Workbench.
2. Create a database named:

```sql
CREATE DATABASE wildlife;
```

3. Import the `wildlife.sql` file.
4. Update the database credentials in `Connector.java`.

Example:

```java
String url = "jdbc:mysql://localhost:3306/wildlife";
String username = "root";
String password = "your_password";
```

---

## ▶️ How to Run

1. Import the project into Eclipse as a Maven Project.
2. Configure Apache Tomcat.
3. Import the `wildlife.sql` database.
4. Update MySQL credentials.
5. Run the project using:

```
Run As → Run on Server
```

6. Open in your browser:

```
http://localhost:8080/WildTour/
```

---

## 📸 Modules

- Home
- Login
- Register
- About
- Safari Booking
- Photography
- Wildlife Sightings
- Tour Packages
- Accommodation
- Guide Services
- Booked Trips
- Contact

---

## 🎯 Learning Outcomes

- Java Full Stack Development
- JSP & Servlet Development
- JDBC Database Connectivity
- CRUD Operations
- Frontend Development
- Database Design
- MVC Architecture
- Git & GitHub Version Control
- Web Application Deployment
- Debugging and Problem Solving

---

## 🚀 Future Enhancements

- Online Payment Gateway
- Email Notifications
- Google Maps Integration
- AI-based Tour Recommendations
- User Reviews & Ratings
- Admin Dashboard
- Mobile Responsive UI
- Spring Boot Backend
- React Frontend

---

