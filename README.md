# ABCU Course Advising Program

## Overview
This project is an academic advising assistance tool developed for the Computer Science Department at **ABCU**.  
It was created as part of the **CS 300 – Data Structures and Algorithms** course at **Southern New Hampshire University**.

The application allows students and advisors to efficiently load, search, and view course data using a **Binary Search Tree (BST)** data structure.  
It demonstrates file handling, sorting, and efficient search operations in C++ while following clean object-oriented design principles.

---

## Features
- **Load Course Data:** Reads course information from a CSV file into a Binary Search Tree.  
- **Default File Support:** Automatically loads from `CS 300 ABCU_Advising_Program_Input.csv` if no file name is entered.  
- **Display All Courses:** Prints all courses in alphanumeric order by course number.  
- **Course Lookup:** Displays full course details and prerequisites for a selected course.  
- **Error Handling:** Handles missing files and invalid menu input gracefully.  

---

## Example File Format
The input CSV file must include one course per line in the following format:


---

## How It Works
1. The program loads data from a CSV file into a **Binary Search Tree**.  
2. Each node in the tree represents a course, with ordering based on the course number.  
3. Users interact through a menu to:
   - Load course data  
   - Print a sorted course list  
   - Look up detailed information for a specific course  

The tree structure ensures efficient lookups and sorted traversal for course listings.

---

## Menu Options
| Option | Description |
|:-------:|:------------|
| **1** | Load course data (press Enter for default file) |
| **2** | Print all courses in sorted order |
| **3** | Search and display details for a single course |
| **9** | Exit the program |

---

## Usage Instructions
### Build and Run
1. Open the project in your preferred C++ IDE (Visual Studio, Code::Blocks, or g++).
2. Compile the source file (e.g., `main.cpp`).
3. Run the executable.

Example console session:
