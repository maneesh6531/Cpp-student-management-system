📘 Student Report Card Management System (C++)

A simple console-based Student Report Card Management System built using Object-Oriented Programming (OOP) in C++.
The system allows adding, viewing, and searching student records.
All data is stored in a text file (students.txt) for persistence.


Student_Management_System

📂 Project Files

File	Description

Student_Management_System	Main C++ source code containing the full implementation

🎯 Features

Add new student details

Calculate total marks, percentage, and grade

Save records in a file permanently

View all existing records

Search a student by roll number

Simple menu-driven system

Fully implemented using OOP + File Handling

🗂️ How the System Works
➤ 1. Add Student

The program asks for:

Roll Number

Name

Marks in Maths, Physics, Chemistry

It automatically calculates:

Total Marks

Percentage

Grade (A, B, C, D, F)

Then it writes everything into students.txt.

➤ 2. View All Students

Displays:

Roll No

Name

Individual subject marks

Total marks

Percentage

Grade

Records are read directly from the file.

➤ 3. Search Student

Enter a roll number → program displays the matching student’s details.

🧮 Grade Calculation Logic
90% and above     → A  
75% - 89%         → B  
60% - 74%         → C  
40% - 59%         → D  
Below 40%         → F

🛠️ Compilation & Execution
✔ Windows (MinGW)
g++ -o student "Student_Management_System"
student.exe

✔ Linux / macOS
g++ -o student "Student_Management_System"
./student

📄 Data Storage Format

Each record is stored in this format:

rollNo name maths physics chemistry total percentage grade


Example:

97 Manu 90 90 90 270 90.00 A

🔧 Technologies Used

C++

OOP Concepts

File Handling (fstream)

Standard I/O

🚀 Future Improvements

Add update & delete options

Add GUI using Qt

Store records in CSV or database

Improve input validation

Handle multi-word names accurately

📌 Author

Karlapudi Maneesh
