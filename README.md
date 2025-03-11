# **Python Learning Roadmap**

---

## **Phase 1: Python Fundamentals**
### **Goal:**
Learn the basics of Python syntax, data types, control flow, and functions.

### **Topics to Cover:**
1. **Introduction to Python:**
   - What is Python?
   - Setting up the environment (Python installation, IDEs like PyCharm, VS Code, or Jupyter Notebook).
   - Writing your first Python program (Hello World).
2. **Variables and Data Types:**
   - Variables and assignments.
   - Data types (`int`, `float`, `str`, `bool`, `list`, `tuple`, `dict`, `set`).
   - Type conversion.
3. **Operators:**
   - Arithmetic operators (`+`, `-`, `*`, `/`, `%`, `**`).
   - Comparison operators (`==`, `!=`, `>`, `<`, `>=`, `<=`).
   - Logical operators (`and`, `or`, `not`).
4. **Control Flow:**
   - Conditional statements (`if`, `elif`, `else`).
   - Loops (`for`, `while`).
   - Loop control statements (`break`, `continue`, `pass`).
5. **Functions:**
   - Defining and calling functions.
   - Function arguments and return values.
   - Lambda functions.
6. **Strings:**
   - String manipulation (`len()`, `split()`, `join()`, `replace()`, etc.).
   - String formatting (`f-strings`, `format()`).
7. **Lists and Tuples:**
   - List operations (append, remove, slice, etc.).
   - Tuple immutability.
8. **Dictionaries and Sets:**
   - Dictionary operations (add, remove, update, etc.).
   - Set operations (union, intersection, difference).

### **Problem Statements:**
1. Write a program to calculate the sum of two numbers.
2. Write a program to check if a number is even or odd.
3. Write a program to find the largest number in a list.
4. Write a program to reverse a string.
5. Write a function to calculate the factorial of a number.
6. Create a dictionary to store student names and their grades. Write functions to add, remove, and update grades.

---

## **Phase 2: Object-Oriented Programming (OOP)**
### **Goal:**
Understand and implement core OOP concepts in Python.

### **Topics to Cover:**
1. **Classes and Objects:**
   - Defining classes and creating objects.
   - Instance variables and methods.
   - Constructors (`__init__` method).
   - The `self` keyword.
2. **Inheritance:**
   - Extending classes using inheritance.
   - Method overriding.
   - The `super()` function.
3. **Polymorphism:**
   - Method overloading (not natively supported, but simulated).
   - Method overriding.
4. **Encapsulation:**
   - Private members (using `_` and `__`).
   - Getters and setters.
5. **Abstraction:**
   - Abstract classes and methods using the `abc` module.
6. **Special Methods:**
   - `__str__`, `__repr__`, `__len__`, etc.

### **Problem Statements:**
1. Create a `Person` class with attributes like `name`, `age`, and `gender`. Add methods to display the person's details.
2. Create a `BankAccount` class with methods to deposit, withdraw, and check balance.
3. Implement a `Shape` class with methods `area()` and `perimeter()`. Extend it for `Circle` and `Rectangle`.
4. Create an interface `Playable` with a method `play()`. Implement it in classes `MusicPlayer` and `VideoPlayer`.
5. Write a program to demonstrate method overriding.

---

## **Phase 3: Data Structures and Algorithms (DSA)**
### **Goal:**
Learn and implement basic data structures and algorithms in Python.

### **Topics to Cover:**
1. **Arrays and Lists:**
   - Single-dimensional and multi-dimensional lists.
   - Common operations (insertion, deletion, searching, sorting).
2. **Linked Lists:**
   - Singly linked lists.
   - Doubly linked lists.
3. **Stacks and Queues:**
   - Stack operations (push, pop, peek).
   - Queue operations (enqueue, dequeue).
4. **Trees:**
   - Binary trees.
   - Binary search trees (BST).
   - Tree traversal (in-order, pre-order, post-order).
5. **Sorting Algorithms:**
   - Bubble Sort.
   - Selection Sort.
   - Insertion Sort.
6. **Searching Algorithms:**
   - Linear Search.
   - Binary Search.

### **Problem Statements:**
1. Implement a stack using lists.
2. Write a program to reverse a linked list.
3. Implement a binary search algorithm.
4. Write a program to perform bubble sort on a list.
5. Create a binary search tree and implement insertion and traversal methods.

---

## **Phase 4: File Handling and Exception Handling**
### **Goal:**
Learn to handle files and exceptions in Python.

### **Topics to Cover:**
1. **File Handling:**
   - Reading from files (`open()`, `read()`, `readlines()`).
   - Writing to files (`write()`, `writelines()`).
   - Working with CSV files (`csv` module).
2. **Exception Handling:**
   - `try`, `except`, `finally` blocks.
   - Custom exceptions.
   - Raising exceptions.

### **Problem Statements:**
1. Write a program to read a file and count the number of words in it.
2. Write a program to write user input to a file.
3. Create a custom exception for invalid age input.
4. Write a program to handle division by zero using exception handling.
5. Implement a program to copy contents from one file to another.

---

## **Phase 5: Advanced Python Concepts**
### **Goal:**
Learn advanced Python concepts like decorators, generators, and working with APIs.

### **Topics to Cover:**
1. **Decorators:**
   - Creating and using decorators.
2. **Generators:**
   - Creating generators using `yield`.
3. **Regular Expressions:**
   - Pattern matching using the `re` module.
4. **Working with APIs:**
   - Making HTTP requests using the `requests` module.
   - Parsing JSON data.
5. **Database Connectivity:**
   - Connecting to databases using `sqlite3`.
   - Executing SQL queries.

### **Problem Statements:**
1. Write a decorator to measure the execution time of a function.
2. Use regular expressions to validate an email address.
3. Write a program to fetch data from a public API (e.g., OpenWeatherMap) and display it.
4. Create a SQLite database to store student records. Write functions to add, update, and retrieve records.
5. Write a generator function to generate Fibonacci numbers.

---

## **Final Project: To-Do List Application**
### **Goal:**
Build a complete Python application to manage a to-do list.

### **Requirements:**
1. **Features:**
   - Add a new task.
   - View all tasks.
   - Mark a task as completed.
   - Delete a task.
   - Save and load tasks to/from a file or database.
2. **Implementation:**
   - Use OOP principles (classes, inheritance, polymorphism).
   - Use file handling or a database for data persistence.
   - Handle exceptions (e.g., invalid input, file not found).
   - Add a simple console-based menu for user interaction.

### **Steps to Complete the Project:**
1. Design the class structure (e.g., `Task`, `ToDoList`).
2. Implement the core functionality (add, view, complete, delete).
3. Add file handling or database connectivity.
4. Write unit tests for critical methods.
5. Refactor and optimize the code.

---