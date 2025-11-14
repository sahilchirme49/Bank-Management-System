


# 🏦 Bank Management System

A full-featured **JavaFX + MySQL** banking application that allows employees and customers to manage core banking operations such as account creation, deposits, withdrawals, and more — all with a simple graphical interface.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [System Requirements](#system-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## 🚀 Overview

The **Bank Management System** is a Java-based desktop application designed to simplify daily banking tasks.  
It allows employees to manage customer data and perform basic banking transactions securely through a MySQL database.

This project demonstrates database connectivity (JDBC), CRUD operations, and UI development using **JavaFX** — making it ideal for learning or academic projects.

---

## ✨ Features

- 👩‍💼 **Employee Module** – Register and manage branch employees.  
- 💳 **Account Module** – Create and maintain customer accounts.  
- 💰 **Transaction Module** – Deposit, withdraw, and check balances.  
- 🧾 **Service Module** – Access extra services like loans, insurance, and bill payments.  
- 🧠 **Database-Driven** – Uses MySQL for persistent storage of all records.  
- 🔄 **Full CRUD Support** – Create, Read, Update, Delete functionality implemented.

---

## 🧰 Tech Stack

| Component         | Technology Used |
|------------------|----------------|
| Front-End (UI)   | JavaFX |
| Backend Logic     | Java (JDK 8+) |
| Database          | MySQL (via XAMPP) |
| IDE (Recommended) | NetBeans 8.2 / Eclipse |
| Build Tool        | Ant / Manual Compile |

---

## 💻 System Requirements

- **Operating System:** Windows 7/10/11 (or later)
- **Java Version:** JDK 8 or newer  
- **IDE:** NetBeans / Eclipse  
- **Database:** MySQL (via XAMPP or standalone)

---

## ⚙️ Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/sahilchirme49/Bank-Management-System.git
   cd Bank-Management-System
   ````

2. **Set Up the Database**

   * Start MySQL from XAMPP.
   * Create a new schema named `bankdb`.
   * Import the provided SQL file:

     ```bash
     mysql -u root -p bankdb < bank.sql
     ```

3. **Configure Database Connection**

   * Open the project in your IDE.
   * Update database credentials in the `DBConnection.java` or similar file:

     ```java
     String url = "jdbc:mysql://localhost:3306/bankdb";
     String user = "root";
     String password = "";
     ```

4. **Run the Application**

   * Build and run the project.
   * The main JavaFX window will appear.
   * Start creating accounts, managing transactions, etc.

---

## 🧭 Usage

* **Employees** can log in or register new accounts.
* **Customers** can open new accounts, view balances, and perform transactions.
* **Admins** can monitor overall operations and manage users.

---

## 🗂️ Project Structure

```
Bank-Management-System/
├── src/                  # Java source files
├── lib/                  # External dependencies (if any)
├── bank.sql              # Database schema & sample data
├── EERDiagram_Bank.png   # Database ER diagram
├── build.xml             # Ant build script
└── README.md             # Project documentation
```

---

## 🤝 Contributing

Contributions are always welcome!

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes and push:

   ```bash
   git push origin feature/your-feature
   ```
4. Open a Pull Request.

Make sure to write clean code and meaningful commit messages.

---

---

### 💬 Author

**Sahil Chirme**
Java Developer | React Enthusiast | IT Engineering Student
📧 [sahilchirme49@gmail.com](mailto:sahilchirme49@gmail.com)

