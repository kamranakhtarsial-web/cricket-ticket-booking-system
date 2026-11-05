# 🏏 Cricket Ticket Booking System

A menu-driven **Cricket Ticket Booking System** created in Python. This project enables users to view available stadium seats, make ticket reservations, monitor booking statuses, inspect stadium seat maps, and generate summary reports for match tickets.

---

## 📌 Project Overview

The system handles match tickets using structured data structures where each ticket record retains three main properties:

* **Seat Number:** A unique 3-digit numerical identifier (e.g., `101`, `102`).
* **Seat Category:** The seating tier (`VIP`, `Premium`, or `General`).
* **Booking Status:** Live seat state (`Available` or `Sold`).

All seats start in an `Available` state. Once a user completes a purchase, the system updates that seat's status to `Sold` in real time.

---

## ✨ System Features

1. **📋 Display All Tickets**
   * Renders a full overview of all 100 stadium seats with seat numbers, categories, pricing, and live status.

2. **🔍 Search Ticket**
   * Look up detailed information for any specific seat number instantly.

3. **🎟️ Book Tickets**
   * Reserve one or multiple tickets in a single transaction.
   * Prevents double-booking of seats that are already marked as `Sold`.
   * Validates user input for non-existent seat numbers and quantities.

4. **🟢 Display Available Tickets**
   * Filters and displays only seats currently open for reservation.

5. **🔴 Display Sold Tickets**
   * Filters and lists seats that have been successfully booked.

6. **📊 Remaining Tickets & Statistics**
   * Calculates total ticket counts, total sold, total available, revenue generated, and sales percentage.

7. **🗺️ Stadium Seat Map**
   * Provides a visual grid layout of stadium seats where booked seats display as `[XXX]`.

---

## 🛠️ Python Concepts Applied

This repository demonstrates essential core programming practices:

* Data structures and custom object representation
* Input parsing and validation logic
* Controlled iteration using `for` and `while` loops
* Conditional branching (`if`, `elif`, `else`)
* Modular function architecture using snake_case conventions
* Index assignment and state persistence across interactive sessions

---

## 📂 Project Structure

```text
cricket-ticket-booking-system/
│
├── notebooks/
│   └── ticket-booking-system.ipynb
│
├── .gitignore
└── README.md
```

---

## 🚀 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/kamranakhtarsial-web/cricket-ticket-booking-system.git
   ```

2. **Navigate into the folder:**

   ```bash
   cd cricket-ticket-booking-system
   ```

3. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

4. Open `notebooks/ticket-booking-system.ipynb` and run the cells sequentially.

---

## 💻 Application Interface Menu

```text
=================================
     CRICKET TICKET SYSTEM
=================================
1. Display All Tickets
2. Search Ticket
3. Book Ticket
4. Display Available Tickets
5. Display Sold Tickets
6. Remaining Tickets
7. View Seat Map
8. Exit
=================================
```

---

## 🎯 Learning Objectives

This project builds practical experience in developing terminal-based Python applications:

* Designing modular interactive control flow loops.
* Maintaining consistent state in memory during user interaction.
* Structuring clean code using Python conventions (PEP 8 / snake_case).
* Preparing organized repositories with standard project documentation.

---

**Language:** Python 🐍 | **Environment:** Jupyter Notebook 📓