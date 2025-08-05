Student Record Management System
Overview
This is a command-line interface (CLI) based Student Record Management System implemented in Java. It allows users to perform CRUD (Create, Read, Update, Delete) operations on student records, which include student ID, name, and marks. The system uses an ArrayList to store student objects and provides a menu-driven interface for ease of use.
Features

Add Student: Create a new student record with a unique ID, name, and marks (0-100).
View All Students: Display all stored student records.
Update Student: Modify a student's name or marks based on their ID.
Delete Student: Remove a student record using their ID.
Input Validation: Ensures valid inputs for ID (unique, numeric) and marks (between 0 and 100).
Error Handling: Gracefully handles invalid inputs and provides user-friendly error messages.

Usage

Launch the program to see the main menu with the following options:
1. Add Student: Enter a unique student ID (numeric), name, and marks (0-100).
2. View All Students: Displays a list of all student records.
3. Update Student: Enter the student ID to update their name or marks. Press Enter to skip updating a field.
4. Delete Student: Enter the student ID to remove their record.
5. Exit: Closes the program.


Follow the prompts to input data. The system validates inputs and provides feedback for errors (e.g., duplicate IDs, invalid marks).

Example
=== Student Record Management System ===
1. Add Student
2. View All Students
3. Update Student
4. Delete Student
5. Exit
Enter your choice: 1
Enter Student ID: 101
Enter Student Name: John Doe
Enter Student Marks: 85.5
Student added successfully!

Project Structure

StudentManagementSystem.java: Contains the main program with the Student class and the CLI interface logic.

Notes

The program uses an ArrayList to store student records in memory, so data is not persisted between sessions.
Input validation ensures robust operation, preventing issues like non-numeric IDs or invalid marks.
The code is well-documented with clear method names and follows object-oriented principles.

Troubleshooting

Compilation Error: Ensure JDK is installed and configured correctly.
Invalid Input: If you enter non-numeric values for ID or marks, the program will display an error and prompt you to try again.
Student Not Found: When updating or deleting, ensure the ID exists in the system.

Future Enhancements

Add file I/O to persist student records between sessions.
Implement additional fields (e.g., email, course).
Add sorting or filtering options for viewing students.

