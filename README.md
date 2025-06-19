# Blood Bank Management System (BBMS)
Relational database design project for a Blood Bank Management System | CPS 430 Term Project

This repository contains documentation and diagrams for a comprehensive **Blood Bank Management System (BBMS)** developed as a group project for CPS 430 – Database Management at the University of Dayton (Spring 2024).

## 📌 Overview

Manual blood bank tracking systems are inefficient, error-prone, and often result in waste or shortages. Our proposed solution implements a structured **database management system** to streamline operations related to donor management, blood inventory, hospital requests, and patient data. 

The system features:
- Efficient blood stock and expiry tracking
- Streamlined donor and recipient data management
- Hospital and blood bank coordination via request records
- Entity-Relationship design and normalized schema
- SQL insert/query examples

## 👥 Team Members

- Yaswanth Ijjurotula  
- Darshan Jigala Channa Reddy  
- Vinitha Uppunuru  
- Shayna Guilfoyle  
- Sharanya Saravanan  
- Nischay Kamshetty  

## 📂 Project Files

- `BBMS_Report.docx` – Full project documentation  
- `BLOOD_BANK_MANAGEMENT_SYSTEM_PROJECT.pptx` – Final presentation slides  
- `BBMS_ERD.jpg` – Entity Relationship Diagram (ERD)  
- `Database Schema BBMS.png` – Database table schema  
- `Referential Integrity BBMS.jpeg` – Diagram of referential integrity constraints  
- `SCHEMA_BBMS.docx` – Table definitions  
- `OracleDATA.docx` – Sample insert statements  
- `Queries.docx` – Example SQL queries  

## 🧠 Core Entities & Relationships

- **Patient** → Hospital admission  
- **Hospital** → Sends blood requests  
- **Request** → Routed to blood banks or camps  
- **Donor** → Donates to banks or camps  
- **Inventory** → Tracked by blood banks  
- **Blood_Stored** → Tracked at blood camps  
- All key tables are normalized and linked with proper referential integrity constraints.

## 🛠 Tools & Technologies

- Oracle SQL  
- ERD & schema tools  
- Microsoft Word / PowerPoint  
- Relational database design principles

---

> 📝 This project was completed as part of the coursework for **CPS 430: Database Management** at the University of Dayton, Spring 2024.
