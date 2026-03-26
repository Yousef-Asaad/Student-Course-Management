# Student Course Management System (C++)

## Project Description

This project is a **C++ console application** designed to manage students and their enrolled courses.
It allows the user to add students, remove students, search for students, enroll them in courses, and sort them based on GPA.

The system also saves student data in a file (`students.txt`) so that information can be stored.

---

## Features

* Add a new student
* Remove a student
* Search for a student by ID
* Display all students
* Enroll a student in a course
* Display student courses
* Sort students by GPA
* Save data to a text file

---

## Required Software

To run this project you need:

* Visual Studio 2019 or later
* C++ Compiler supporting C++11 or later
* Windows OS (recommended)

---

## Project Structure

```
Student-Course-Management
│
├── main.cpp
├── students.txt
├── README.md
└── Project_Report.pdf
```

---

## How to Compile and Run

### Using Visual Studio

1. Open Visual Studio.
2. Open the project folder.
3. Open the file `main.cpp`.
4. Build the project using:

```
Ctrl + F5
```

or click **Start Without Debugging**.

5. The console menu will appear.

---

## Program Menu

The program provides the following menu:

1. Add Student
2. Remove Student
3. Search Student
4. Display Students
5. Enroll Course
6. Show Student Courses
7. Sort Students by GPA
8. Exit

The user selects an option by entering the corresponding number.

---

## Data Storage

Student data is saved in a text file called:

```
students.txt
```

The file stores:

* Student ID
* Student Name
* GPA
* Number of courses
* Course names

---

## Notes

* Each student must have a **unique ID**.
* GPA must be between **0.0 and 4.0**.
* The system prevents duplicate course entries.

---

## Author

Yousef Asaad
