[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15317402&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics

What is Python?
Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming. Python's design philosophy emphasizes code readability and simplicity, which makes it accessible to beginners and allows developers to express concepts with fewer lines of code compared to other languages.

Key Features of Python:

    Simple and Easy to Learn: Python has a straightforward syntax that emphasizes readability and reduces the cost of program maintenance.
    Interpreted: Python code is executed line by line at runtime, which facilitates rapid development and debugging.
    Extensive Standard Library: Python comes with a large standard library that provides modules and packages for various tasks, from working with files to web development.
    Dynamic Typing: Python is dynamically typed, meaning you don't need to declare variables with their data types. Types are inferred at runtime.
    Cross-platform: Python runs on various platforms like Windows, macOS, and Linux, making it highly versatile.

Use Cases:

    Web Development: Frameworks like Django and Flask are popular for building web applications.
    Data Science and Machine Learning: Python's libraries (e.g., NumPy, Pandas, scikit-learn) make it ideal for data analysis, machine learning, and scientific computing.
    Automation: Python is used for scripting and automation tasks, such as system administration and deployment scripts.
    Prototyping: Due to its simplicity and rapid development capabilities, Python is often used for prototyping new software ideas.

2. Installing Python

Windows:

    Download Python installer from python.org.
    Run the installer, select "Add Python to PATH," and follow prompts to install.
    Open Command Prompt or PowerShell and verify Python installation:

    sh

python --version


sh

    python -m venv myenv
    myenv\Scripts\activate



Verify installation:

sh

python3 --version



3. Python Syntax and Semantics

python

# Hello, World! program
print("Hello, World!")

    Explanation:
        print(): Python function that outputs text to the console.
        "Hello, World!": String literal enclosed in double quotes.

4. Data Types and Variables

Basic Data Types:

    Integer (int): Whole numbers (-3, 0, 42).
    Float (float): Floating point numbers (3.14, -0.001).
    String (str): Sequence of characters ("hello", 'world').
    Boolean (bool): Represents truth values (True, False).

Example Script:

python

# Variables and data types
num1 = 10
num2 = 3.5
name = "Alice"
is_valid = True

# Printing variables
print(num1)
print(num2)
print(name)
print(is_valid)

5. Control Structures

Conditional Statements (if-else):

python

# Example of if-else statement
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")

Loops (for loop):

python

# Example of for loop
for i in range(5):
    print(i)

6. Functions in Python

Definition and Usage:

python

# Function to add two numbers
def add_numbers(a, b):
    return a + b

# Calling the function
result = add_numbers(3, 5)
print("Sum:", result)

7. Lists and Dictionaries

Lists (list):

python

# Creating a list of numbers
numbers = [1, 2, 3, 4, 5]

# Accessing elements
print(numbers[0])  # Output: 1

# Modifying elements
numbers.append(6)
print(numbers)  # Output: [1, 2, 3, 4, 5, 6]

Dictionaries (dict):

python

# Creating a dictionary of key-value pairs
person = {
    "name": "Alice",
    "age": 30,
    "city": "New York"
}

# Accessing values by keys
print(person["name"])  # Output: Alice

# Modifying values
person["age"] = 31
print(person)  # Output: {'name': 'Alice', 'age': 31, 'city': 'New York'}

8. Exception Handling

Using try, except, and finally:

python

# Example of exception handling
try:
    num = int(input("Enter a number: "))
    result = 10 / num
    print("Result:", result)
except ZeroDivisionError:
    print("Error: Cannot divide by zero!")
except ValueError:
    print("Error: Invalid input! Please enter a number.")
finally:
    print("Execution completed.")

9. Modules and Packages

Modules: Python files containing functions, classes, and variables.

python

# Example of importing a module
import math

# Using functions from math module
print(math.sqrt(16))  # Output: 4.0

Packages: Collection of modules. Install using pip and use with import.
10. File I/O

Reading from a File:

python

# Reading from a file
with open('file.txt', 'r') as file:
    content = file.read()
    print(content)

Writing to a File:

python

# Writing to a file
data = ["Hello", "World", "Python"]
with open('output.txt', 'w') as file:
    for line in data:
        file.write(line + '\n')

These examples cover fundamental aspects of Python programming. Feel free to explore and experiment further with Python to deepen your understanding!

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


