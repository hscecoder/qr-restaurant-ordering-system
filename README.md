# 🍽️ QR-Based Restaurant Ordering System

## 1. Project Overview

The **QR-Based Restaurant Ordering System** is a real-world software application that allows customers to scan a QR code placed on their table, view the digital menu, select food items, and place orders using their smartphones.

The system reduces waiting time, minimizes manual ordering errors, and helps restaurant staff manage orders efficiently.

---

## 2. Objectives

* Provide a fast and contactless ordering system.
* Reduce manual errors in taking orders.
* Improve customer experience.
* Allow restaurant staff to manage orders digitally.
* Apply **Software Engineering and Design Principles** in a real-world project.

---

## 3. 👥 Project Team

| S.No. | Team Member         | Responsibility                  |
| ----- | ------------------- | ------------------------------- |
| 1     | Himanshu Soni       | Project Planning & Coordination |
| 2     | Hemant Kumar        | Frontend Development            |
| 3     | Ayush Shrivastava   | Backend & Database              |
| 4     | Harshit Shrivastava | Testing & Documentation         |

---

# 4. 🛠️ Tech Stack

| Technology | Purpose                            |
| ---------- | ---------------------------------- |
| HTML       | Web page structure                 |
| CSS        | UI design and styling              |
| JavaScript | Frontend functionality             |
| Node.js    | Backend runtime                    |
| Express.js | REST API                           |
| MySQL      | Database                           |
| QR Code    | Table identification               |
| Git        | Version control                    |
| GitHub     | Collaboration & repository hosting |

---

# 5. 🏗️ System Architecture

The system follows a **three-layer architecture**:

```text
┌──────────────────────┐
│     Customer UI      │
│  HTML/CSS/JavaScript │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│    Backend / API     │
│    Node.js/Express   │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│       Database       │
│        MySQL         │
└──────────────────────┘
```

---

# 6. 📂 Repository Structure

```text
qr-restaurant-ordering-system/
│
├── frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── components/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   └── models/
│
├── database/
│   └── schema.sql
│
├── tests/
│   ├── unit/
│   └── integration/
│
├── docs/
│   ├── requirements.md
│   └── design.md
│
├── .gitignore
├── README.md
└── package.json
```

---

# 7. 🔄 System Flow

```text
Customer
   ↓
Scan Table QR Code
   ↓
Digital Menu
   ↓
Select Food
   ↓
Add to Cart
   ↓
Place Order
   ↓
Backend API
   ↓
MySQL Database
   ↓
Restaurant Dashboard
   ↓
Order Preparation
   ↓
Order Completed
```

---

# 8. 🔧 Software Engineering & Design Principles

The project applies the following principles:

### Modularity

The system is divided into separate frontend, backend, database, and testing modules.

### Separation of Concerns

User interface, business logic, and database operations are kept separate.

### DRY — Don't Repeat Yourself

Reusable functions and components are used to avoid duplicate code.

### KISS — Keep It Simple

The system is designed with simple and understandable workflows.

### Single Responsibility Principle

Each module/class is responsible for a specific task.

### Maintainability

A structured repository and clear code organization make the project easier to modify and maintain.

### Scalability

The architecture allows additional features such as online payment, notifications, and multiple restaurants to be added later.

---

# 9. 🧪 Testing

Testing is performed to ensure that the system works correctly and reliably.

| Test Type           | Purpose                                                 |
| ------------------- | ------------------------------------------------------- |
| Unit Testing        | Test individual functions/modules                       |
| Integration Testing | Test interaction between frontend, backend and database |
| System Testing      | Test the complete ordering system                       |
| UI Testing          | Check menu, cart and ordering interface                 |
| Validation Testing  | Check invalid input and order data                      |

### Example Test Cases

| Test Case            | Expected Result               |
| -------------------- | ----------------------------- |
| Scan valid QR code   | Correct menu opens            |
| Add food to cart     | Food appears in cart          |
| Remove food          | Food is removed               |
| Place valid order    | Order is successfully created |
| Empty cart           | Order cannot be placed        |
| Staff updates status | Customer sees updated status  |

---

# 10. 🐙 Git & GitHub Version Control

The project uses **Git and GitHub** for source-code management and team collaboration.

### Clone Repository

```bash
git clone <repository-url>
cd qr-restaurant-ordering-system
```

### Check Status

```bash
git status
```

### Add Changes

```bash
git add .
```

### Commit Changes

```bash
git commit -m "Add restaurant menu"
```

### Push Changes

```bash
git push origin main
```

### Create Feature Branch

```bash
git checkout -b feature/menu
```

### Merge Feature

```bash
git checkout main
git merge feature/menu
git push origin main
```

### View History

```bash
git log --oneline
```

---

# 11. 🌿 Git Workflow

```text
Create Feature
      ↓
Create Branch
      ↓
Write / Modify Code
      ↓
Test Code
      ↓
git add
      ↓
git commit
      ↓
git push
      ↓
Pull Request
      ↓
Code Review
      ↓
Merge into Main
```

---

# 12. 🐙 Repository

**Repository Name:** `qr-restaurant-ordering-system`

The GitHub repository contains:

* Source code
* Database files
* Documentation
* Test cases
* README
* Version history

---

# 13. 📸 Project Demonstration Evidence

The following screenshots can be included in the project report:

1. GitHub repository creation
2. Repository homepage
3. Repository structure
4. `git status`
5. `git add`
6. `git commit`
7. `git push`
8. GitHub commit history
9. Feature branch
10. Pull Request and merge
11. QR code scanning
12. Digital menu
13. Cart and order placement
14. Restaurant order dashboard
15. Testing results

---

# 14. 🎯 Expected Outcome

The system will provide a simple, reliable, and efficient restaurant ordering experience while demonstrating important **Software Engineering and Design Principles**, including modularity, separation of concerns, maintainability, testing, version control, and team collaboration.

---

## 📌 Project Information

**Project:** QR-Based Restaurant Ordering System
**Subject:** Software Engineering and Design Principles
**Team Size:** 4 Members
**Repository:** `qr-restaurant-ordering-system`
**Version:** 1.0
