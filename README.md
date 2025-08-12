# Gladiator-Project
This is another Project which is developed by me along with a team of 4 members. Where we used Angular for frontend, Spring Boot for the middle tag and MySQL for the backed. Investment Tracking is a full Stack Web Development Project where there are user and admin roles. User can track their Investments made by the Admin. 

Technologies Used
Frontend: Angular 10
Backend: Spring Boot 3.0.1
Database: MySQL 8
Security: Spring Security with JWT
Java Version: 17

Features
User Features
View available properties
Submit property inquiries
Add feedback for properties
Track inquiry status
User authentication and authorization
Responsive user interface

Admin Features
Property management (Add/Edit/Delete)
View and manage user inquiries
View user feedback
Admin control panel
Property listing management
Prerequisites
Node.js and npm
Angular CLI 10.x
Java Development Kit (JDK) 17
MySQL 8.x
Maven


Installation & Setup
Clone the Repository
cd investtrack
Frontend Setup (Angular)
cd angularapp
npm install
ng serve
The frontend will be available at http://localhost:4200


Backend Setup (Spring Boot)
cd springapp
mvn clean install
mvn spring:boot run
The backend will start at http://localhost:8080


Database Configuration
The application uses MySQL. Update the database configuration in springapp/src/main/resources/application.properties:
spring.datasource.url=jdbc:mysql://localhost/appdb?createDatabaseIfNotExist=true
spring.datasource.username=your_username
spring.datasource.password=your_password
Project Structure

Frontend Components
Home Page: Landing page for the application
Authentication: Login and Registration components
User Dashboard: Inquiry management
Admin Panel: Investment and user management interface
Feedback System: User feedback submission and admin review

Backend Structure
RESTful APIs for property management
User authentication and authorization
Database integration
File handling for property images


Security configurations
Security
JWT based authentication
Role-based access control (User/Admin)
Password encryption using BCrypt
Protected API endpoints
