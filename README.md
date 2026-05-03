# Pharmacy Management System (C++)

A modular C++ application designed to manage pharmacy inventory and customer reservations using object-oriented principles and file-based persistence.

---

## Overview

This project implements a simple pharmacy management system with two distinct roles:

- **Admin** – manages products (CRUD operations)
- **User** – browses available products and creates reservations

The application focuses on clean architecture, modular design, and core C++ concepts.

---

## Features

- Product management (Create, Read, Update, Delete)
- Reservation system
- CSV-based data persistence
- Separate execution flows for Admin and User

---

## Project Structure
├── main_admin.cpp # Entry point for admin functionality
├── main_user.cpp # Entry point for user functionality
│
├── classes/
│ ├── Produs # Product model
│ ├── Rezervare # Reservation model
│ ├── Utilizator # User model
│ ├── Admin # Admin logic
│ └── Repository # Data access layer
│
└── files/
├── produse.csv # Product storage
└── rezervari.csv # Reservation storage


---

## ⚙️ Build & Run

### Compile
```bash
g++ main_admin.cpp -o admin
g++ main_user.cpp -o user
Run
./admin
./user
