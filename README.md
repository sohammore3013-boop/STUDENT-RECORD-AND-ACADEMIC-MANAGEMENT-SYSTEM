# 🎓 Student Record and Academic Management System

A menu-driven, command-line application developed using **Python** to manage student records and academic information. The project demonstrates the practical use of Python data structures, functions, loops, conditional statements, and input validation.

The system allows users to add, search, update, and delete student records, manage academic details, and generate reports such as average marks, highest scorer, and department-wise student lists.

## ✨ Features

### 1. Student Record Management
- **Add Student:** Register students with their personal and academic details.
- **Search Student:** Find a student's record using their roll number.
- **Update Student:** Modify student information, department, subjects, marks, and attendance.
- **Delete Student:** Remove a student record with confirmation.
- **Display All Records:** View all registered students and their details.

### 2. Academic Management
- Store subject-wise marks and attendance percentages.
- Calculate the total and average marks of a student.
- Identify the student with the highest average marks.
- View students belonging to a particular department.
- Count the total number of registered students.

### 3. Reports and Statistics
- Display unique departments.
- Display unique subjects.
- Display student clubs.
- Generate academic reports.
- View all student records from the report menu.

### 4. Input Validation
- Prevent empty text inputs.
- Accept only positive integers for roll numbers and subject counts.
- Validate marks within the range of 0–100.
- Validate attendance percentages within the range of 0–100.
- Check for duplicate roll numbers before adding a student.
- Handle invalid numeric inputs without terminating the program.
  

## 🧠 Python Concepts Demonstrated

This project demonstrates the use of the following Python concepts:

| Concept | Application in the Project |
|---|---|
| Lists | Store student records, subjects, marks, and attendance |
| Tuples | Store student identity details |
| Dictionaries | Organize individual student records |
| Sets | Maintain unique departments, subjects, and clubs |
| Functions | Divide the program into reusable modules |
| Loops | Handle menus, input validation, and record traversal |
| Conditional Statements | Implement menu choices and decision-making |
| Exception Handling | Handle invalid numeric inputs using `try-except` |
| List Methods | Add and remove student records |
| Set Methods | Maintain collections of unique values |
| String Methods | Process user inputs and perform case-insensitive department searches |
| Data Validation | Ensure valid marks, attendance, and required inputs |

## 🖥️ Application Menu

When the program starts, the following main menu is displayed:

```text
============================================================
       STUDENT RECORD AND ACADEMIC MANAGEMENT SYSTEM
============================================================

1.  Add Student
2.  Search Student
3.  Update Student Record
4.  Delete Student Record
5.  Display All Records
6.  Calculate Average Marks
7.  Find Highest Scorer
8.  List Students by Department
9.  Count Students
10. Generate Reports
11. Exit
```

Enter the corresponding number to select an operation.

The **Generate Reports** option provides additional features, including unique department and subject lists, student clubs, and academic statistics.

## 📂 Project Structure

```text
Student-Record-Management-System/
│
├── main.py
└── README.md
```

*Note: This is an example structure. Replace `main.py` with your actual Python filename and add any other project files present in your repository.*

## 📊 How It Works

1. The user selects an operation from the main menu.
2. The program collects and validates the required information.
3. Student details are stored in a dictionary.
4. Each student dictionary is stored in the main list of student records.
5. The program uses the roll number to locate individual student records.
6. Academic functions process marks and attendance to generate results.
7. The report menu displays statistics and unique values maintained using sets.


## 🎯 Project Objective

The primary objective of this project is to develop a simple student management application while applying fundamental Python programming concepts to a practical problem.

It also serves as a foundation for learning modular programming, data organization, input validation, and basic application development.

## 👨‍💻 Author

**Soham More**

Student Developer | Python Programming

⭐ If you find this project useful, consider giving the repository a star on GitHub!
