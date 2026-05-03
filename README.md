Pharmacy Management System (C++)

A lightweight, modular C++ application for managing pharmacy inventory and reservations using object-oriented design and file-based persistence.

Overview

This project implements a simple pharmacy management system with two distinct roles:

Admin → manages products (CRUD operations)
User → browses products & creates reservations

The focus is on clean architecture, modularity, and core C++ concepts.

Features
Product management (Add / Update / Delete / List)
Reservation system
CSV-based persistence
Separate execution flows (Admin vs User)
Project Structure

.
├── main_admin.cpp      # Admin entry point
├── main_user.cpp       # User entry point
│
├── classes/
│   ├── Produs          # Product model
│   ├── Rezervare       # Reservation model
│   ├── Utilizator      # User model
│   ├── Admin           # Admin logic
│   └── Repository      # Data handling layer
│
└── files/
    ├── produse.csv
    └── rezervari.csv
Build & Run
# Compile
g++ main_admin.cpp -o admin
g++ main_user.cpp -o user

# Run
./admin
./user
Technical Highlights
Object-Oriented Design
clear separation of responsibilities
domain-driven structure
STL Usage
std::vector for in-memory storage
File Handling
CSV parsing for persistence
C++ Features
operator overloading (<<)
modular compilation
Possible Improvements
Authentication & roles system
Search & filtering
Database integration (SQLite / PostgreSQL)
GUI (Qt / web interface)
Why this project?

This project demonstrates:

ability to design modular C++ applications
understanding of data persistence without external dependencies
writing clean, maintainable code
