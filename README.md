# 🚆 IRCTC Ticket Booking System

A console-based Java application that simulates an IRCTC-style railway ticket booking system using file-based JSON storage and a clean service-oriented architecture.

---

## 📌 Features

- User registration and authentication
- Train and route management
- Ticket booking functionality
- Seat availability tracking using 2D arrays
- Persistent storage using JSON files
- Modular and readable code structure

---

## 🛠 Tech Stack

- Java
- Gradle
- JSON (Local Database)
- IntelliJ IDEA / VS Code

---

## 📂 Project Structure

IRCTC/
├── app/
│ ├── src/main/java/ticket/booking/
│ │ ├── App.java
│ │ ├── entities/
│ │ │ ├── User.java
│ │ │ ├── Train.java
│ │ │ └── Ticket.java
│ │ ├── services/
│ │ │ ├── TrainService.java
│ │ │ └── UserBookingService.java
│ │ └── util/
│ │ └── UserServiceUtil.java
│ │
│ ├── src/main/resources/ticket/booking/localDb/
│ │ ├── users.json
│ │ └── trains.json
│ │
│ └── src/test/java/ticket/booking/
│ └── AppTest.java
│
├── build.gradle
├── settings.gradle
├── gradlew
└── README.md



🔐 Notes

- Passwords are stored in hashed format
- This project is for learning and demonstration purposes
- Not intended for production use



🚀 Future Scope

- Spring Boot REST API
- Database integration
- Seat locking and waitlist logic
- Web or mobile frontend


👨‍💻 Author

Nitin Saini
