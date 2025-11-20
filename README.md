# Student-Task-Manager
A robust, console-based Python application designed to help students manage their academic tasks and track their academic performance. This project features data persistence, meaning all tasks and grades are saved automatically to local files.

# Features
1. **To-Do List Manager** 
* *Add Tasks*: Quickly add new tasks to your list.
* *View Tasks*: See your pending and completed tasks with status indicators (e.g., [x] or [ ]).
* *Mark as Complete*: Update task status when you finish work.
* *Remove Tasks*: Delete unwanted items from the list.
* *Auto-Save*: All changes are saved instantly to tasks.json.

2. **Grade Manager & CGPA Calculator** 
* *Add Subjects*: Input subject names, marks obtained (0-100), and course credits (e.g., 4.0).
* *View Grades*: See a formatted list of all your entered subjects and scores.
* *Edit Records*: Update marks or credits if you made a mistake or improved your score.
* *Calculate CGPA*: automatically calculates your Weighted Grade Point Average based on the credits and marks provided.
* *Auto-Save*: All academic data is saved to marks.json.

# Project Structure
* This project demonstrates Modular Programming by separating logic into distinct files for better maintainability and readability:
* *main.py*: The entry point of the application. Handles the main menu and navigation.
* *todo_manager.py*: Contains all logic for managing the To-Do list operations.
* *grade_manager.py*: Contains logic for handling grades, credits, and CGPA calculations.
* *file_handler.py*: A utility module that handles all File I/O (Input/Output) operations using the JSON format.

# Tools used
* *Python Fundamentals*: Loops, Conditionals, Functions, and Data Structures (Lists, Dictionaries).
* *File Handling*: Reading and writing data using the json module.
* *Error Handling*: Robust use of try...except blocks to prevent crashes from invalid user input (e.g., entering text when a number is required).
* *Algorithm Design*: Logic for searching lists, calculating weighted averages, and managing state flags.

# Future possible changes
* This program is made to manage a student's day-to-day tasks so just these 2 functions are not enough.
* My aim is to add more functions like health tracker , Notes handling , to be able to create small quizes from the uploaded notes(For this task I wish to learn ai to train a model for this specific task.
* I also wish to make the program GUI(*Graphical user interface*) based.
