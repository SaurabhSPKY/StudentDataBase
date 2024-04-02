
# Student Database Management System (SDBMS)

This is a simple Java program for managing student records using a HashMap data structure.

## Features

- Add a new student record.
- View all student records.
- Search for a student by roll number.
- Calculate the average marks of all students.
- Exit the program.

## Key Concepts Used in the code:
## Classes
#### 1.Student Class:
  -Represents a student with attributes such as name, roll number, age, and marks.
  -Contains a constructor to initialize the student object.
  -Includes a method viewStudent() to display the details of a student.

## Data Structure
#### 1.HashMap:
-Used to store student objects with roll numbers as keys.
-Allows efficient retrieval of student information based on roll numbers.

## Input Handling
#### 1.Scanner Class:
-Utilized to take input from the user through the command line.
-Reads user input for adding, viewing, searching, and performing operations on student data.

## Menu-Driven Interface
#### 1.Switch Case:
-Implements a menu-driven interface using a switch-case construct.
-Allows users to choose different options such as adding a student, viewing students, searching for a student, 
  calculating average marks, and exiting the program.

## Operations
#### 1.Add Student:
  -Prompts the user to input student details (name, roll number, age, marks).
  -Creates a Student object and adds it to the HashMap with roll number as the key.

#### 2.View Student:
  -Displays details of all students stored in the HashMap.

##### 3.Search Student:
  -Prompts the user to input a roll number to search for a specific student.
  -Retrieves and displays the details of the student with the given roll number if found.

#### 4.Calculate Average Marks:
-Calculates the average marks of all the students stored in the HashMap.
-Displays the calculated average.

#### 5.Exit:
-Terminates the program execution.

## Looping
#### 1.Infinite Loop:
-The program runs in an infinite loop until the user chooses to exit.

## Exception Handling
#### 1.Invalid Choice:
-Handles invalid user inputs by displaying an appropriate message.

