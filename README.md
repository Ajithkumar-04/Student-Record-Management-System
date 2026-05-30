.......................*Student Record Management System*.....................................
*****Overview*****

A menu-driven Student Record Management System developed in C using a Singly Linked List and File Handling concepts.

The application allows users to add, delete, modify, display, sort, reverse, and save student records through an interactive command-line interface.

This project demonstrates the use of dynamic memory allocation, linked lists, structures, modular programming, and CSV file handling.

*****Features****
Add new student records
Automatic roll number allocation
Delete records by:
Roll Number
Student Name
Modify records by:
Roll Number
Name
Percentage
Display all student records
Sort records
By Name
By Percentage
Reverse record display
Delete all records
Save records to CSV file
Menu-driven user interface
Technologies Used
C Programming
Singly Linked List
Dynamic Memory Allocation (malloc)
Structures
File Handling
Modular Programming
Makefile

******Data Structure Used*****
typedef struct st
{
    int rollno;
    char name[50];
    float mark;
    struct st *next;
}ST;

Each student record is stored as a node in a singly linked list.

******Project Structure******
.
├── main.c
├── header.h
├── figure.h
├── student_add.c
├── student_delete.c
├── student_modify.c
├── student_show.c
├── student_save.c
├── student_sort.c
├── student_reverse.c
├── Makefile
└── student.csv
Compilation

___Using Makefile:

make

Or using GCC:

gcc main.c \
student_add.c \
student_delete.c \
student_modify.c \
student_show.c \
student_save.c \
student_sort.c \
student_reverse.c \
-o student
Run the Program
./student


Menu
**** STUDENT RECORD MENU ****

A/a : Add New Record
D/d : Delete a Record
S/s : Show the List
M/m : Modify a Record
V/v : Save the List
T/t : Sort the List
R/r : Reverse the List
L/l : Delete All Records
E/e : Exit


****Sample CSV Output****
RollNo,Name,Percentage
1,Ajith,91.50
2,Ravi,85.00
3,Kumar,88.25

****Concepts Demonstrated***
Linked List Traversal
Dynamic Memory Allocation
Node Insertion
Node Deletion
Searching Techniques
File Handling
Modular Programming
Makefile Usage

****Advantages****
Dynamic memory allocation
Efficient insertion and deletion
Modular design
CSV file storage
User-friendly menu system

****Limitations****
Linear search complexity O(n)
No authentication mechanism
Command-line interface only
No automatic data loading
Suitable for small to medium datasets
Future Enhancements
Load records from CSV on startup
GUI-based application
Database integration (MySQL/SQLite)
User authentication
Search optimization using Trees or Hash Tables
Export reports in PDF format

****Author****

Ajithkumar P R

Bachelor of Engineering (Honours) – Electronics and Communication Engineering


LinkedIn: linkedin.com/in/ajithkumar-p-r-554b9522b
