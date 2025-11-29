# Traffic Management System (TMS)

A comprehensive academic project developed to practically apply Object-Oriented Programming (OOP) concepts using Java, aimed at achieving efficient and organized traffic flow management and violation recording.

---

## Table of Contents

- [Background and Academic Context](#background-and-academic-context)
- [Core System Features and Functionalities](#core-system-features-and-functionalities)
- [System Structure and OOP Implementation](#system-structure-and-oop-implementation)
- [Technology Stack](#technology-stack)
- [Teamwork and Contribution](#teamwork-and-contribution)

---

## Background and Academic Context

This project was developed as a fundamental requirement for the **Object-Oriented Programming (OOP)** course at the **Faculty of Computer and Information Sciences, Ain Shams University**.

**Goal:** To create a robust traffic management system that serves as a practical demonstration of core OOP principles such as Encapsulation, Inheritance, Polymorphism, and Abstraction.

---

## Core System Features and Functionalities

The system is designed to meet the needs of three primary user roles, ensuring clear separation of responsibilities:

### Admin Functionalities

* Add, update, or delete traffic lights and configure their operating durations.
* View and analyze traffic violations by vehicle or specific zone.
* Generate comprehensive traffic reports, including high-density zones and frequent violations.

### Traffic Officer Functionalities

* Record new violations by entering the vehicle ID, violation type, and date.
* View all violations recorded by themselves.

### Vehicle Owner Functionalities

* Secure login to the system.
* View all violations registered against their vehicles.
* Functionality to pay outstanding fines online.
* Check vehicle status and registered details.

---

## System Structure and OOP Implementation

The system design relies on a Class Diagram representing real-world entities:

| Class | Key Attributes | Responsibilities |
| :--- | :--- | :--- |
| **TrafficLight** | ID, Location, Status, Duration | Manages the light cycle and configuration. |
| **Vehicle** | ID, Type, License Plate, Owner | Represents vehicles and their basic details. |
| **Owner** | ID, Name, Contact Info, List of Vehicles | Manages vehicle owners' data and associated vehicles. |
| **TrafficViolation** | ID, Vehicle ID, Type, Date, Fine Amount | Records and tracks violation details. |
| **TrafficOfficer** | ID, Name, Contact Info, Assigned Zone | Records violations and views personal records. |
| **Zone** | ID, Name, Location, List of Traffic Lights | Defines specific traffic areas and manages lights within. |

### Implemented OOP Concepts

* **Encapsulation:** Achieved by declaring attributes as `private` and accessing them via `public` methods (Getters/Setters).
* **Inheritance:** (Mention if `Car`, `Truck`, `Bike` inherit from `Vehicle`).
* **Polymorphism:** (Mention where methods with the same name behave differently across classes).
* **Abstraction:** Used to separate interfaces from their underlying implementations.

### Data Persistence & Design Constraints

To ensure efficient data handling and maintain clean code architecture, data persistence (reading and writing system data) strictly adhered to the following design constraints:

* **Optimized File Handling:** The entire system utilizes **only two dedicated functions** for all file reading and writing operations.
* **Purpose:** This constraint was implemented to centralize data management logic, enhancing **maintainability** and demonstrating proficiency in **resource management** within the OOP paradigm.

---

## Technology Stack

| Technology | Role |
| :--- | :--- |
| **Java (JDK 8+)** | Primary language for system development. |
| **Git & GitHub** | Version control and collaborative development. |
| **IDE** | IntelliJ. |

---

## Teamwork and Contribution

This project was developed through **collaborative teamwork** as part of the academic requirements for the OOP course.

* **Team Size:** The project was executed by a **team of 7 students**.
* **Work Period:** The core requirements were completed between **November 17, 2024,** and **December 21, 2024**.

### My Key Contribution

**My primary focus was on the design and implementation of the critical Vehicle Owner Functionalities**, ensuring a smooth and secure user experience. My responsibilities included:

* Designing and implementing the secure **Owner Login** mechanism.
* Programming the interfaces and methods required for **viewing all registered violations**.
* Developing the functionality for **online fine payment**.
* Building the necessary logic to **check vehicle status** and display registration details.

---

