# 🩸 S.H.Y. Organization: Blood Bank Management System

![Java](https://img.shields.io/badge/Java-Spring_Boot-green)
![Database](https://img.shields.io/badge/Database-H2_Console-blue)
![Architecture](https://img.shields.io/badge/Architecture-MVC-orange)
![Frontend](https://img.shields.io/badge/Frontend-Thymeleaf_%2F_HTML-red)

**S.H.Y. Organization** is a comprehensive web-based Blood Bank Management System developed for the **CSC3402: Database Application Development** course at **Universiti Putra Malaysia (UPM)**.

The system serves as a centralized platform to streamline the blood donation process, managing data for donors, patients, and blood inventory efficiently while raising awareness about blood donation.

---

## 🎯 Project Objectives

* [cite_start]**Streamline Operations:** Aids blood banks in managing donor data and tracking blood supplies efficiently[cite: 16].
* [cite_start]**Encourage Donors:** Guides first-time donors through the process to increase participation[cite: 9].
* [cite_start]**Raise Awareness:** Educates users on the importance of blood donation and health recovery[cite: 12].

---

## 🛠️ Tech Stack & Architecture

[cite_start]The application follows the **Model-View-Controller (MVC)** architectural pattern to ensure separation of concerns and scalable code structure[cite: 176].

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Backend** | Java (Spring Boot) | Handles business logic (Service Layer) and request processing (Controller Layer). |
| **Database** | H2 Console | [cite_start]Relational database for storing Donor, Patient, and Blood Bank records[cite: 195]. |
| **Frontend** | HTML / CSS | [cite_start]User interfaces for Login, Registration, and Dashboards[cite: 713]. |
| **ORM** | JPA / Hibernate | [cite_start]Maps Java objects (DTOs) to database tables[cite: 190]. |
| **Design Tools** | ERD Plus / GoodNotes | [cite_start]Used for Database Schema and UI Wireframing[cite: 70, 71]. |

---

## 🚀 Key Features

### 1. User Roles & Authentication
* [cite_start]**Guest/Public:** Can view information about doctors, refreshments, and recovery tips[cite: 385, 408].
* [cite_start]**Donor:** Secure registration and login to book appointments and view donation history[cite: 121].
* [cite_start]**Employee (Admin):** Secure login to manage the entire system[cite: 123].

### 2. Core Functionalities (CRUD)
[cite_start]The system implements full **Create, Read, Update, and Delete (CRUD)** operations[cite: 50]:

* [cite_start]**📝 Registration:** New donors can create accounts with personal and medical details[cite: 506].
* [cite_start]**📅 Appointments:** Donors can book appointments (Create) which are saved to the database[cite: 317].
* [cite_start]**📊 Data Management:** Employees can View (Retrieve), Edit (Update), and Remove (Delete) donor and patient records[cite: 536, 555, 556].
* [cite_start]**🏆 Certification:** Automatically generates donation certificates for donors based on their history[cite: 636].

---

## 💾 Database Design

The system is built on a robust relational database schema designed to ensure data integrity.

**Key Entities (ERD):**
* [cite_start]**Donor:** Stores personal info, blood group, and medical history[cite: 137].
* [cite_start]**Blood Bank:** Manages inventory and location details[cite: 148].
* [cite_start]**Appointment:** Links donors to specific time slots[cite: 156].
* [cite_start]**Patient:** Tracks recipients of blood donations[cite: 166].

> *For a detailed view of the Entity Relationship Diagram (ERD), please refer to the documentation included in the repo.*

---

## 👥 Project Team (Group 1)

**Nurfarhannis Nabila Binti Mohd Fauzi** (216535)
* [cite_start]*Role:* Guest Login HTML & Database Implementation[cite: 715].

**Nur Saheerah Binti Rafiq Ravindran** (216408)
* [cite_start]*Role:* Main Website HTML & UI Design[cite: 713].

**Nurul Ilyana Binti Mohamed Saupi** (214695)
* [cite_start]*Role:* Employee Login HTML & Report Management[cite: 729].

---

## ⚙️ Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/hannbella18/projectCSC3402.git](https://github.com/hannbella18/projectCSC3402.git)
    ```
2.  **Open in IDE:** Open the project in IntelliJ IDEA or Eclipse.
3.  **Database Setup:** Ensure H2 Console is configured in `application.properties`.
4.  **Run:** Execute the main Spring Boot application file.
5.  **Access:** Go to `http://localhost:8080` in your browser.

---
