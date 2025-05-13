# Hospital Management System

A simple Java Swing-based Hospital Management System to manage Patients, Doctors, and Appointments.

---

## ✨ Features

* User login interface
* Manage **Patients**: Add, view, and delete
* Manage **Doctors**: Add, view, and delete
* Manage **Appointments**: Add, view, and delete
* GUI built using **Java Swing**
* Uses **ArrayList** for in-memory data management

---

## 📁 Project Structure

```
HospitalManagementSystem/
├── HospitalManagementSystem.java  # Main GUI logic and data models
└── README.md                        # Project overview and usage
```

---

## 📃 Class Descriptions

### Patient

```java
String name, age, disease;
```

Holds information about a patient.

### Doctor

```java
String name, specialty, patientName;
```

Holds information about a doctor and the patient assigned.

### Appointment

```java
String patientName, doctorName, date;
double billAmount;
```

Holds appointment details along with billing information.

---

## 🚀 Getting Started

### Prerequisites

* Java JDK 8 or higher
* IDE or terminal to compile and run Java programs

### How to Run

1. Clone or download the project
2. Compile the Java file:

```bash
javac HospitalManagementSystem.java
```

3. Run the application:

```bash
java shreyas10.HospitalManagementSystem
```

---

## 🔐 Login Credentials

| Username | Password |
| -------- | -------- |
| user     | admin123 |

---

## 🔧 Future Enhancements

* Add file-based or database persistence
* Form input validation (age, date, empty fields)
* Prevent duplicate entries
* Search and filter functionality
* Role-based user access (Admin/Doctor)
* UI improvements with layout managers or JavaFX

---

## 📄 License

This project is open-source and free to use for educational purposes.

---

## ✉️ Author

Developed by **Shreyas10**.
Feel free to contribute or suggest improvements!
