# 🏥 Polyclinic Management System

A comprehensive, web-based Polyclinic Management System designed to streamline clinic operations. This project is built with vanilla PHP, following the MVC (Model-View-Controller) architectural pattern to ensure a structured and maintainable codebase.

---

## ✨ Key Features

This system is equipped with a variety of features to manage clinic activities efficiently:

* **👤 Multi-user Role Management:** Different dashboards and functionalities for Managers, Secretaries, Doctors, and Patients.
* **🔐 Secure Authentication:** Secure login and registration systems for all user types.
* **🗓️ Appointment Scheduling:** Patients can book appointments, and secretaries/doctors can manage them (accept, reject, complete).
* **👨‍⚕️ Doctor Management:** Managers can add, update, and remove doctor profiles and their specialities.
* **👩‍💼 Secretary Management:** Managers can oversee secretary accounts.
* **📋 Consultation Records:** Doctors can create and manage detailed consultation notes for each appointment.
* **🏥 Room & Schedule Management:** Ability to manage clinic rooms and doctor's weekly schedules.
* **🔔 Patient Notifications:** Automated notifications for patients regarding their appointment status.
* **📄 PDF Generation:** Generate reports and appointment details using the TCPDF library.
* **🔍 Search & Filter:** Robust search functionality to filter appointments, doctors, and records by various criteria (name, date, phone number).

---

## 🧑‍🤝‍🧑 User Roles

The system is designed with a clear separation of roles, providing tailored experiences for each user type:

* **👑 Manager:** Has full administrative access. Manages doctors, secretaries, specialities, and rooms.
* **🩺 Doctor:** Manages their appointments, writes consultation notes, sets fees, and views their schedule.
* **📝 Secretary:** Manages all clinic appointments, handles booking, and can print patient records.
* **🤒 Patient:** Can sign up, book appointments with doctors, view their appointment history, and receive notifications.
* **👤 Guest:** Can view the clinic's public information and doctor specialities before logging in.

---

## 🏛️ Architecture

The application is built using the **Model-View-Controller (MVC)** pattern:

* **📁 `Model/`**: Contains the PHP classes that represent the application's data structure (e.g., `Appointment.php`, `Doctor.php`, `Patient.php`). These classes are responsible for interacting with the database.
* **📁 `View/`**: Holds all the presentation files. This includes UI components, pages for different user roles, and CSS stylesheets. It's responsible for displaying data to the user.
* **📁 `Controller/`**: Acts as the intermediary between the Model and the View. It handles user requests, processes data (with the help of the Model), and decides which View to render.

---

## 💻 Technology Stack

* **Backend:** PHP
* **Frontend:** HTML5, CSS3
* **Database:** MySQL (implied through PHP usage)
* **PDF Generation:** [TCPDF](https://github.com/tecnickcom/TCPDF)
* **Server:** A web server with PHP support (e.g., Apache, Nginx) is required.
