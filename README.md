# UTMS - University Bus Management System 🚌

**UTMS** is a lightweight, core Java-based application designed to streamline the transportation system of a university. Instead of using a traditional database (like SQL), this project relies entirely on **Java File Handling (File I/O)** to store, retrieve, and manage data persistently using `.txt` or `.dat` files. It is an ideal academic project demonstrating Object-Oriented Programming (OOP) principles and file operations.

## 🌟 Key Features

*   **Role-Based Access:** Separate login systems for Administrators and Students.
*   **Admin Module:**
    *   Add, update, or remove bus details and routes.
    *   Manage bus timings and available seats.
    *   View all student booking records.
*   **Student Module:**
    *   View available buses based on routes and schedules.
    *   Book seats for a specific route.
    *   Cancel bookings and view ticket details.
*   **Data Persistence:** All records (users, buses, routes, and tickets) are securely saved and read from local text files, ensuring data is not lost after the program closes.

## 🛠️️ Tech Stack

*   **Language:** Java (Core Java / Java SE)
*   **Concepts Used:** Object-Oriented Programming (OOP), Collections Framework, Exception Handling
*   **Storage:** Java File I/O (`FileReader`, `FileWriter`, `BufferedReader`, `ObjectOutputStream`)
*   **Interface:** Command Line Interface (CLI) / Console-based
