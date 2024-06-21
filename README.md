[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15306372&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
Python is a high-level, interpreted programming language known for its readability and simplicity. Some key features that make Python popular include:

Easy to Read and Write: Python’s syntax is clear and concise, making it easy for beginners to learn and use.
Interpreted Language: Python code is executed line-by-line, which makes debugging easier.
Dynamically Typed: You don’t need to declare the type of a variable; it is inferred at runtime.
Extensive Standard Library: Python has a rich standard library that provides tools suited to many tasks.
Portability: Python can run on different operating systems like Windows, macOS, and Linux without requiring modification to the code.
Support for Multiple Paradigms: Python supports procedural, object-oriented, and functional programming styles.
Use Cases:

Web Development: Using frameworks like Django and Flask.
Data Science and Machine Learning: Using libraries like Pandas, NumPy, and TensorFlow.
Automation and Scripting: Writing scripts to automate repetitive tasks.
Software Development: Building desktop and server-side applications.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
 Windows:

Download the Python installer from python.org.
Run the installer and ensure the option "Add Python to PATH" is checked.
Follow the installation steps.
Verify the installation by opening Command Prompt and running: code python --version  

Setting Up a Virtual Environment:

Create a virtual environment: code python3 -m venv myenv
Activate the virtual environment:
Windows: myenv\Scripts\activate
macOS/Linux: source myenv/bin/activate
Deactivate the virtual environment: code deactivate

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
print("Hello, World!")
Explanation:
print: This is a built-in function in Python that outputs text to the console.
"Hello, World!": This is a string literal enclosed in double quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
Basic Data Types:
int: Integer numbers, e.g., 1, 2, 3.
float: Floating-point numbers, e.g., 1.0, 2.5, 3.14.
str: Strings, e.g., "hello", "world".
bool: Boolean values, e.g., True, False.
list: Ordered collection of items, e.g., [1, 2, 3].
dict: Key-value pairs, e.g., {"key": "value"}.
tuple: Immutable ordered collection of items, e.g., (1, 2, 3).
set: Unordered collection of unique items, e.g., {1, 2, 3}.
Script:
python code
# Creating variables of different data types
integer_var = 10
float_var = 20.5
string_var = "Hello, Python"
bool_var = True
list_var = [1, 2, 3, 4, 5]
dict_var = {"name": "Alice", "age": 25}

# Printing variables
print("Integer:", integer_var)
print("Float:", float_var)
print("String:", string_var)
print("Boolean:", bool_var)
print("List:", list_var)
print("Dictionary:", dict_var)
5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
Conditional Statements:
Conditional statements allow you to execute different blocks of code based on certain conditions.
Example:
python code
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
Loops:
Loops allow you to execute a block of code multiple times.

Example of a For Loop:
python code
for i in range(5):
    print("Iteration:", i)
6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
Functions are reusable blocks of code that perform a specific task. They help in organizing code, making it more modular and easier to manage.
Example:
python code
def add_numbers(a, b):
    return a + b

# Calling the function
result = add_numbers(3, 5)
print("Sum:", result)
7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
Differences:
Lists: Ordered collection of items, accessed by index. e.g., [1, 2, 3]
Dictionaries: Unordered collection of key-value pairs, accessed by key. e.g., {"name": "Alice", "age": 25}
Script:
python code
# List of numbers
numbers = [1, 2, 3, 4, 5]
print("Original List:", numbers)
numbers.append(6)
print("List after appending 6:", numbers)

# Dictionary with key-value pairs
person = {"name": "Alice", "age": 25}
print("Original Dictionary:", person)
person["age"] = 26
print("Dictionary after updating age:", person)
8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
Exception handling is a mechanism to handle runtime errors, allowing the program to continue execution.
Example:
python code
try:
    result = 10 / 0
except ZeroDivisionError as e:
    print("Error:", e)
finally:
    print("This block is executed no matter what.")
9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
Modules: A module is a file containing Python definitions and statements. It can define functions, classes, and variables.
Packages: A package is a collection of modules in directories that give a package hierarchy.
Example of Importing a Module:
python code
import math
print("Pi:", math.pi)
print("Square root of 16:", math.sqrt(16))
10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
Reading from a File:
python code
with open('example.txt', 'r') as file:
    content = file.read()
    print("File Content:\n", content)
Writing to a File:
python code
lines = ["First line", "Second line", "Third line"]
with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + "\n")    

References:
Python Official Documentation: https://docs.python.org/3/
Real Python: https://realpython.com/

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


