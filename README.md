💊 Pharmacy Management System (C++)
📌 Overview

A modular C++ application for managing pharmacy inventory and reservations, built using object-oriented design and file-based persistence.

The system provides two roles:

Admin – manages products (CRUD operations)
User – browses products and creates reservations
⚙️ Core Features
Product management (add, update, delete, list)
Reservation system
CSV-based data persistence
Separation between admin and user flows
🧱 Architecture
Domain classes: Produs, Rezervare, Utilizator, Admin
Repository layer: handles file I/O and in-memory storage (std::vector)
Utilities: parsing and helper functions
Entry points:
main_admin.cpp
main_user.cpp
💾 Data Storage

Data is stored in CSV files:

produse.csv
rezervari.csv
🚀 Build & Run
g++ main_admin.cpp -o admin
g++ main_user.cpp -o user

./admin
./user
🧠 Technical Highlights
Object-Oriented Design (encapsulation, separation of concerns)
STL usage (std::vector)
File handling (CSV parsing)
Operator overloading (<<)
Modular project structure
📈 Future Improvements
Authentication system
Search & filtering
Better validation
Transition to database (e.g. SQLite)
