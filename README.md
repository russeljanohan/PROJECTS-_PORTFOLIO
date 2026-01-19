# Laboratory 1 – Library Book Management System

## Overview
In this laboratory, you will develop a simple **Library Book Management System** in Java.  
The program is intended to help librarians keep track of books and their availability. Users can add new books, update their status, view all books, and generate a brief report summarizing the collection.

---

## Goals
- Implement basic Java programming concepts including arrays, loops, and conditionals  
- Create a menu-driven program for user interaction  
- Design methods to modularize code (`addBook()`, `updateBookStatus()`, `showBooks()`, `generateReport()`)  
- Handle invalid inputs gracefully and exit the program cleanly

---

## Java Concepts Applied
- Arrays for storing book information  
- Methods for modular code  
- Loops and conditional statements  
- Switch-case for menu selection  
- Input validation

---

## Project Structure
Laboratory01-LibraryBookManagement/
├── src/
│ └── Main.java
└── README.md

---


### File Details
- **Lab1JavaReview.java** – Implements the menu system, handles user input, and contains all methods to manage books.

---

## Instructions to Run
1. Open the project folder in a Java IDE (Eclipse, NetBeans, IntelliJ IDEA).  
2. Navigate to the `src` folder and run `Lab1JavaReview.java`.  
3. Follow the on-screen menu to interact with the system: add books, update status, view books, and generate reports.

---

## Features
- **Book Registration**: Add new books (maximum 5), default status is “Available”.  
- **Status Updates**: Toggle between “Available” and “Borrowed” for each book.  
- **Display Books**: Shows a list of all books with their current status.  
- **Report Generation**: Summarizes total books, available books, and borrowed books.  
- **Input Validation**: Invalid menu selections or book numbers are handled properly.  
- **Exit**: Program closes with a friendly message.

---

## Notes
- Each method is designed to follow the lab instructions closely.  
- Book data is stored in an array, and the program ensures the maximum limit is enforced.  
- The program emphasizes clean code, readability, and user-friendly console output.

