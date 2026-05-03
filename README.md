# Pharmacy Management System (C++)

A modular C++ application for managing pharmacy inventory and reservations, built using object-oriented design and file-based persistence.

---

## Overview

The system supports two roles:

* **Admin** – manages products (create, update, delete)
* **User** – browses products and creates reservations

---

## Features

* Product management (CRUD operations)
* Reservation handling
* CSV-based data storage
* Separate admin and user workflows

---

## Architecture

The application follows a modular structure with clear separation of concerns:

* **Models**: Product, Reservation, User
* **Logic Layer**: Admin operations
* **Data Layer**: Repository (CSV handling)

---

## Build & Run

```bash
g++ main_admin.cpp -o admin
g++ main_user.cpp -o user

./admin
./user
```

---

## Technical Highlights

* Object-oriented design
* STL usage (`std::vector`)
* File handling with CSV
* Operator overloading (`<<`)

---

## Future Improvements

* Authentication system
* Search & filtering
* Database integration
* GUI (Qt or web)

---

## Summary

This project demonstrates the ability to design and implement a structured C++ application with modular architecture and persistent storage.
It is made by a two man team. 
My first ever team project.
