Experiment – 5
Title
Implementation of Set and Dictionary in Python
________________________________________
Aim
To study and implement set data structure in Python and perform various set and Dictionary operations.
________________________________________
Objectives
•	To understand the concept of sets
•	To perform set creation and basic operations
•	To apply mathematical set operations
•	To understand dictionary structure
•	To perform insertion, deletion, and access of data
•	To apply dictionary methods
________________________________________
Theory on Sets
A set in Python is an unordered collection of unique elements.
Sets are defined using curly braces {} or the set() constructor.
Characteristics of Set
•	Unordered
•	No duplicate elements
•	Mutable
•	Does not support indexing
Sets are commonly used in real-life scenarios such as removing duplicates, membership testing, and mathematical operations.
________________________________________
Set Operations
•	Union
•	Intersection
•	Difference
•	Symmetric Difference
________________________________________
Program 1: Creating a Set and Displaying Elements
fruits = {"apple", "banana", "cherry"}
print("Fruits:", fruits)
________________________________________
Program 2: Removing Duplicate Values
numbers = {1, 2, 3, 2, 4, 1}
print("Unique numbers:", numbers)
________________________________________
Program 3: Set Operations
A = {1, 2, 3, 4}
B = {3, 4, 5, 6}

print("Union:", A | B)
print("Intersection:", A & B)
print("Difference:", A - B)
print("Symmetric Difference:", A ^ B)
________________________________________
Program 4: Set Methods
s = {10, 20, 30}
s.add(40)
s.remove(20)

print("Updated Set:", s)
________________________________________
Applications of Set
•	Removing duplicate records
•	Membership testing
•	Mathematical computations
________________________________________

Theory on dictionary
A dictionary is an unordered collection of key-value pairs.
Each key must be unique, while values may be duplicated.
Syntax:
dictionary = {key: value}
Dictionaries are widely used in real-life applications such as student records, phone books, and configuration data.
________________________________________
Characteristics of Dictionary
•	Key-value based
•	Mutable
•	Keys are unique
•	Values can be modified
________________________________________
Program 1: Creating and Accessing Dictionary
student = {
    "roll": 101,
    "name": "Amit",
    "branch": "CSE"
}

print("Name:", student["name"])
________________________________________
Program 2: Adding and Updating Elements
student["year"] = "Second"
student["name"] = "Rahul"

print(student)
________________________________________
Program 3: Removing Elements
student.pop("branch")
print("After removal:", student)
________________________________________
Program 4: Dictionary Methods
print("Keys:", student.keys())
print("Values:", student.values())
print("Items:", student.items())
________________________________________
Program 5: Iterating Through Dictionary
for key, value in student.items():
    print(key, ":", value)
________________________________________
Applications of Dictionary
•	Student information systems
•	Phone directories
•	Database records
•	Configuration files
________________________________________

Conclusion
Sets efficiently handle unique data and support mathematical operations, making them useful for data processing tasks.
Dictionaries provide efficient storage and retrieval of data using keys, making them essential for real-world applications.

