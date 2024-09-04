HOSPITAL MANAGEMENT SYSTEM USING C

Patient Record System
Overview

A simple patient record system implemented in C using a linked list data structure. This system allows users to insert, delete, search, and display patient records.

Features

- Insert patient records with ID, name, age, disease, and bed number
- Delete patient records by name
- Search patient records by name
- Display all patient records in a tabular format
- Count the total number of patient records

Usage

1. Compile the program using gcc (e.g., gcc patient_record_system.c -o patient_record_system)
2. Run the program (e.g., ./patient_record_system)
3. Follow the menu-driven interface to perform operations

Requirements

- C compiler (e.g., gcc)
- C standard library headers (stdio.h, stdlib.h, string.h, conio.h)

Known Issues

- No error handling for memory allocation failures
- No input validation for buffer overflows
- No data persistence (records are lost when the program exits)

Future Enhancements

- Add error handling and input validation
- Implement data persistence using files or a database
- Improve user interface and experience


