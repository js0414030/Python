Introduction

Python is a high-level, interpreted programming language known for its simplicity and readability. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

1. Variables and Data Types

Definition:

A variable is a symbolic name for a value that is stored in memory. Python is dynamically typed, meaning you don't need to declare variable types explicitly.

Syntax:

x = 10       # Integer
y = 3.14     # Float
z = "Python" # String
is_valid = True  # Boolean

Type Checking:

print(type(x))   # Output: <class 'int'>
print(type(y))   # Output: <class 'float'>
print(type(z))   # Output: <class 'str'>

Type Conversion:

print(int(3.5))   # Output: 3
print(float(3))   # Output: 3.0
print(str(123))   # Output: '123'

2. Operators

Python provides different types of operators for mathematical and logical operations.

Arithmetic Operators:

Operator

Description

Example

+

Addition

x + y

-

Subtraction

x - y

*

Multiplication

x * y

/

Division

x / y

//

Floor Division

x // y

%

Modulus

x % y

**

Exponentiation

x ** y

Comparison Operators:

print(5 == 5)  # True
print(5 != 3)  # True
print(5 > 3)   # True
print(5 < 3)   # False

Logical Operators:

print(True and False)  # False
print(True or False)   # True
print(not True)        # False

3. Control Flow

Conditional Statements:

x = 10
if x > 0:
    print("Positive")
elif x < 0:
    print("Negative")
else:
    print("Zero")

Loops:

for Loop:

for i in range(5):
    print(i)  # Prints 0 to 4

while Loop:

n = 5
while n > 0:
    print(n)
    n -= 1

Loop Control Statements:

for i in range(5):
    if i == 2:
        break  # Stops loop at 2
    if i == 1:
        continue  # Skips 1
    print(i)

4. Functions

Definition:

A function is a block of reusable code that performs a specific task.

Syntax:

def greet(name):
    return f"Hello, {name}!"

print(greet("Jatin"))  # Output: Hello, Jatin!

Lambda Functions:

add = lambda x, y: x + y
print(add(2, 3))  # Output: 5

5. Data Structures

Lists (Mutable):

my_list = [1, 2, 3, "Python"]
print(my_list[0])  # Output: 1
my_list.append(4)
print(my_list)  # Output: [1, 2, 3, 'Python', 4]

Tuples (Immutable):

my_tuple = (1, 2, 3, "Python")
print(my_tuple[1])  # Output: 2

Sets (Unique Elements):

my_set = {1, 2, 3, 3}
print(my_set)  # Output: {1, 2, 3}

Dictionaries (Key-Value Pairs):

my_dict = {"name": "Jatin", "age": 20}
print(my_dict["name"])  # Output: Jatin
my_dict["city"] = "Roorkee"

6. String Operations

s = "Hello, Python"
print(s.lower())  # Output: hello, python
print(s.upper())  # Output: HELLO, PYTHON
print(s.split(","))  # Output: ['Hello', ' Python']

7. File Handling

Writing to a File:

with open("file.txt", "w") as f:
    f.write("Hello, Python!")

Reading from a File:

with open("file.txt", "r") as f:
    content = f.read()
    print(content)

8. Exception Handling

Definition:

Exception handling is used to manage runtime errors and prevent program crashes.

try:
    x = 1 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("Execution completed")

9. Importing Libraries

import math
print(math.sqrt(16))  # Output: 4.0

import random
print(random.randint(1, 10))  # Random number between 1 and 10

10. Object-Oriented Programming (OOP)

Defining a Class:

class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def greet(self):
        return f"Hello, my name is {self.name}"

p = Person("Jatin", 20)
print(p.greet())  # Output: Hello, my name is Jatin

Inheritance: