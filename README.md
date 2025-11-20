# LAB_ASSIGN-_JAVA_1
assignment 1

📘 Student Record System – README
📌 Overview

The Student Record System is a simple Java-based console application designed to manage student details.
It uses Object-Oriented Programming (OOP) concepts such as inheritance, encapsulation, and method overriding.

The application allows users to:

Add new student records

Display all stored student records

Automatically calculate grades based on marks

🧱 Features
✔ OOP Concepts Used

Inheritance:
Student class inherits from Person class.

Encapsulation:
Sensitive fields like rollNo, course, marks are private.

Method Overriding:
toString() is overridden to print student details properly.

Input Validation:
Ensures marks are between 0 and 100.

🏗️ Class Structure
1. Person Class

Contains the protected field name.

2. Student Class

Inherits from Person

Contains:

rollNo

course

marks

grade

Methods include:

inputDetails()

calculateGrade()

setMarks()

displayDetails()

Overridden toString()

3. StudentRecordSystem (Main Class)

Uses menu-driven interface to:

Add students

Display all students

Exit application

▶️ How to Run

Save the code as:

StudentRecordSystem.java


Compile using:

javac StudentRecordSystem.java


Run the program:

java StudentRecordSystem

📤 Sample Output
Program Run Example
===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 1
Enter Roll No: 101
Enter Name: Aryan
Enter Course: B.Tech
Enter Marks (0-100): 88

===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 1
Enter Roll No: 102
Enter Name: Neha
Enter Course: BCA
Enter Marks (0-100): 95

===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 2
Roll No: 101
Name: Aryan
Course: B.Tech
Marks: 88.0
Grade: B

Roll No: 102
Name: Neha
Course: BCA
Marks: 95.0
Grade: A

===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 3
Exiting the application. Goodbye!

📝 Grade Calculation
Marks Range	Grade
90–100	A
75–89	B
50–74	C
Below 50	D
🛠️ Technologies Used

Java

ArrayList

Scanner

OOP Principles

