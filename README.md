# python-cheat-sheet
python cheat sheet
# Python Cheat Sheet 📜  

## Table of Contents  
1. [Basics](#basics)  
2. [Data Types & Structures](#data-types--structures)  
3. [Conditionals & Loops](#conditionals--loops)  
4. [Functions](#functions)  
5. [Modules & Packages](#modules--packages)  
6. [File Handling](#file-handling)  
7. [Error Handling](#error-handling)  




# Print statement  
print("Hello, World!")  # Output: Hello, World!  

# Variables (No need to declare types explicitly)  
x = 10        # Integer  
y = 3.14      # Float  
z = "Python"  # String  

# Comments  
# Use '#' for single-line comments  
"""  
Use triple quotes for multi-line comments or docstrings  
"""  
Data Types & Structures
Python provides several built-in data types and structures for managing data efficiently.


# Lists: Ordered, mutable, allows duplicates  
my_list = [1, 2, 3]  
my_list.append(4)    # Adds 4 to the list  
print(my_list)       # [1, 2, 3, 4]  

# Tuples: Ordered, immutable, allows duplicates  
my_tuple = (1, 2, 3)  
print(my_tuple[1])    # Access element by index  

# Sets: Unordered, no duplicates  
my_set = {1, 2, 3}  
my_set.add(4)         # Adds 4 to the set  
print(my_set)         # {1, 2, 3, 4}  

# Dictionaries: Key-value pairs, unordered  
my_dict = {"name": "Alice", "age": 25}  
print(my_dict["name"])  # Access value using key  
Conditionals & Loops
Python supports standard control flow tools to manage program execution.


# If-Else (Conditional execution)  
x = 10  
if x > 5:  
    print("Greater")  # Executes if condition is True  
else:  
    print("Smaller")  

# Loops  
# For loop: Iterates over a range or collection  
for i in range(5):  
    print(i)  # Prints numbers from 0 to 4  

# While loop: Runs until the condition is False  
while x > 0:  
    print(x)  
    x -= 1  # Decrement x to avoid infinite loop  
Functions
Functions allow you to write reusable, modular code.

\
# Function Definition and Usage  
def add(a, b):  
    """Adds two numbers."""  
    return a + b  

print(add(2, 3))  # Output: 5  

# Lambda Functions (Anonymous functions)  
square = lambda x: x ** 2  
print(square(4))  # Output: 16  
Modules & Packages
Modules are reusable code files, and packages are directories of modules.


# Importing Built-in Modules  
import math  
print(math.sqrt(16))  # Output: 4.0  

# Custom Module (Create a file named my_module.py)  
# my_module.py  
def greet():  
    print("Hello!")  

# Use the custom module  
import my_module  
my_module.greet()  # Output: Hello!  
File Handling
Python makes it easy to work with files using open() and context managers.


# Reading a File  
with open("file.txt", "r") as file:  
    content = file.read()  
    print(content)  

# Writing to a File  
with open("file.txt", "w") as file:  
    file.write("Hello, File!")  
Error Handling
Python uses try-except blocks to handle runtime errors gracefully.


try:  
    result = 10 / 0  
except ZeroDivisionError as e:  
    print(f"Error: {e}")  # Output: Error: division by zero  
finally:  
    print("Cleanup!")  # Always executed  




