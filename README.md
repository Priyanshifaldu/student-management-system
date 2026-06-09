# Student Management System

A console-based Java application designed to manage student records efficiently. The system allows users to add, search, update, and delete student information while demonstrating core Object-Oriented Programming (OOP) concepts and custom exception handling.

---

## Features

* Add new student records
* View student details
* Update existing student information
* Delete student records
* Search students by ID
* Custom exception handling
* Modular and maintainable code structure

---

## Technologies Used

* Java
* Object-Oriented Programming (OOP)
* Collections Framework
* Exception Handling

---

## Project Structure

```text
Student-Data-entry/
│
├── Main.java
├── Student.java
├── StudentOperations.java
├── InvalidInputException.java
├── StudentAlreadyExistsException.java
├── StudentNotFoundException.java
├── HowToRun.txt
└── README.md
```

---

## File Description

### Main.java

Entry point of the application. Handles user interaction and menu-driven operations.

### Student.java

Represents the Student entity and stores student-related information.

### StudentOperations.java

Contains methods for performing CRUD operations on student records.

### InvalidInputException.java

Custom exception for handling invalid user inputs.

### StudentAlreadyExistsException.java

Thrown when attempting to add a student whose ID already exists.

### StudentNotFoundException.java

Thrown when a requested student record cannot be found.

---

## OOP Concepts Implemented

* Classes and Objects
* Encapsulation
* Abstraction
* Exception Handling
* Modular Programming

---

## How to Run

### Compile

```bash
javac *.java
```

### Execute

```bash
java Main
```

---

## Sample Operations

* Add Student
* View Student
* Update Student
* Delete Student
* Search Student
* Exit Application

---

## Learning Outcomes

This project demonstrates:

* Java programming fundamentals
* Custom exception creation and handling
* Data management using collections
* Menu-driven application development
* Object-Oriented Design Principles

---

## Author

**Priyanshi Faldu**

Bachelor of Technology (B.Tech)

Artificial Intelligence and Machine Learning

Symbiosis Institute of Technology, Pune

---

## License

This project is developed for academic and educational purposes.
