# 🚗🧼 Car Wash Management System

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![OOP](https://img.shields.io/badge/OOP-Concepts-blue?style=flat)
![Academic](https://img.shields.io/badge/Type-Academic%20Project-purple?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-green?style=flat)

> A Java-based Car Wash Management System built using core Object-Oriented Programming (OOP) principles — developed as part of an OOP academic module at SLIIT City University.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [OOP Concepts Applied](#oop-concepts-applied)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [System Modules](#system-modules)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Author](#author)

---

## 📖 About the Project

The **Car Wash Management System** is a console-based Java application designed to manage the complete operations of a car wash business. The system handles customer registrations, service bookings, billing, and service record tracking — all built using core OOP concepts.

This project was developed as part of the **Object-Oriented Programming (OOP)** module at SLIIT City University, demonstrating practical application of OOP design principles in a real-world business scenario.

---

## 🧩 OOP Concepts Applied

| OOP Concept | How It's Used |
|---|---|
| **Classes & Objects** | Separate classes for Customer, Vehicle, Service, Bill, Employee |
| **Encapsulation** | Private fields with public getters and setters |
| **Inheritance** | Service types extend a base Service class (e.g., BasicWash, PremiumWash) |
| **Polymorphism** | Method overriding for different service pricing and descriptions |
| **Abstraction** | Abstract class for Service with abstract methods |
| **Constructors** | Parameterized constructors for object initialization |
| **ArrayList / Collections** | Managing lists of customers, services, and records |

---

## ✨ Features

| Feature | Description |
|---|---|
| 👤 Customer Management | Register new customers and store their details |
| 🚘 Vehicle Registration | Add and manage customer vehicles |
| 🧼 Service Booking | Book car wash services (Basic, Standard, Premium) |
| 💰 Billing System | Auto-generate bills based on selected services |
| 📋 Service Records | View and track service history per customer |
| 🔍 Search Functionality | Find customers and their records by ID or name |
| 📊 Service Summary | View total services completed and revenue generated |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Java** | Core programming language |
| **OOP Design** | System architecture and class design |
| **Java Collections** | ArrayList for data management |
| **Scanner (Console I/O)** | User input handling |
| **IntelliJ IDEA / Eclipse** | Development IDE |

---

## 🏗️ System Modules

```
Car Wash Management System
│
├── Customer Module
│   ├── Register customer
│   ├── View customer details
│   └── Search customer by ID/name
│
├── Vehicle Module
│   ├── Add vehicle to customer
│   ├── View vehicles
│   └── Update vehicle details
│
├── Service Module
│   ├── Basic Wash
│   ├── Standard Wash
│   ├── Premium Wash
│   └── Custom Service Packages
│
├── Billing Module
│   ├── Generate bill
│   ├── Apply discounts
│   └── Print bill summary
│
└── Records Module
    ├── View service history
    ├── Filter by customer
    └── View total revenue
```

---

## ⚙️ Installation

### Prerequisites
- Java JDK 11 or higher
- IntelliJ IDEA, Eclipse, or any Java IDE
- OR Command line with Java installed

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/YathavanJD/Car_wash_managenent_system.git

# 2. Navigate to project folder
cd Car_wash_managenent_system

# 3. Extract the zip file
# Unzip: OOP prpject.zip

# 4. Open in your IDE
# IntelliJ IDEA: File → Open → Select the project folder
# Eclipse: File → Import → Existing Java Project

# 5. Run the application
# Locate the Main.java file and run it
```

### Running from Command Line

```bash
# Compile
javac Main.java

# Run
java Main
```

---

## 🚀 Usage

Once the application starts, you will be presented with a menu:

```
====== Car Wash Management System ======
1. Register Customer
2. Add Vehicle
3. Book Service
4. Generate Bill
5. View Service History
6. View All Customers
7. Search Customer
8. Exit
=========================================
Enter your choice:
```

Navigate using the numbered menu options to manage customers, vehicles, services, and billing.

---

## 📁 Project Structure

```
Car_wash_managenent_system/
│
├── src/
│   ├── Main.java                  # Entry point / main menu
│   │
│   ├── models/
│   │   ├── Customer.java          # Customer class
│   │   ├── Vehicle.java           # Vehicle class
│   │   ├── Service.java           # Abstract Service base class
│   │   ├── BasicWash.java         # Basic wash service (extends Service)
│   │   ├── StandardWash.java      # Standard wash service (extends Service)
│   │   ├── PremiumWash.java       # Premium wash service (extends Service)
│   │   └── Bill.java              # Billing class
│   │
│   ├── managers/
│   │   ├── CustomerManager.java   # Customer CRUD operations
│   │   ├── ServiceManager.java    # Service booking logic
│   │   └── BillingManager.java    # Bill generation and management
│   │
│   └── utils/
│       └── InputHelper.java       # Input validation utilities
│
├── OOP prpject.zip                # Project archive
├── CODE CRACKERS.zip              # Team project files
└── README.md
```

---

## 📚 Key Learnings

- Designing a real-world system using **OOP principles**
- Implementing **class hierarchies** with inheritance and polymorphism
- Managing **data collections** using Java ArrayList
- Building a **menu-driven console application** with user input validation
- Applying **encapsulation** to protect data integrity across the system
- Working as part of a **team project** (Code Crackers)

---

## 👨‍💻 Author

**Loganathan Yathavan**
- 📧 loganathanyathavan@gmail.com
- 🌐 [Portfolio](https://yathavanjd.github.io/Yathavan_Portfolio/)
- 💼 [LinkedIn](https://www.linkedin.com/in/yathavanloganathan03)
- 🐙 [GitHub](https://github.com/YathavanJD)

---

> ⭐ If you found this project useful, please consider giving it a star!
