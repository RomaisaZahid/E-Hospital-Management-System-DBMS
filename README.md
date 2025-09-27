
# 🏥 E-Hospital Management System

A Database Management System (DBMS) project designed to digitalize hospital operations.  
This project integrates *Java (Swing GUI)* and *Oracle SQL Database* to provide efficient patient management, appointment scheduling, and billing.

---

## 📌 Features
- *Patient Management* – Add, update, and view patient records.  
- *Doctor Management* – Store doctor details and view schedules.  
- *Appointment Scheduling* – Patients can book appointments with doctors.  
- *Billing System* – Generate and manage billing information.  
- *Secure Database* – Data stored safely using Oracle SQL with JDBC connectivity.

---

## 🛠 Technologies Used
- *Frontend:* Java Swing  
- *Backend:* Oracle SQL Database  
- *Connectivity:* JDBC  

---

## 📊 Database Design
Main tables in the system:
- Patients
- Doctors
- Appointments
- Billing

*Relationships:*
- One Patient → Many Appointments  
- One Doctor → Many Appointments  
- One Patient → One Billing  

---

## 🚀 How to Run
Import the project in Eclipse.
Configure Oracle Database and import SQL schema 
Update JDBC connection settings in java files.
Run the project to launch the hospital management system
