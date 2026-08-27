# Exploring-Python-Lists-Dictionaries-Sets-Conditional-Statements

## 📌 Project Overview

This repository contains my Python fundamentals practice exercises, covering important beginner-level concepts such as Lists, Dictionaries, Sets, Operators, and Conditional Statements.

The exercises helped me understand how Python data structures work, how to modify and access elements, and how to apply conditions to solve simple programming problems.

## 🎯 Project Objective

The objective of this project is to practice and understand the fundamental concepts of Python by working with Lists, Dictionaries, Sets, Operators, and Conditional Statements. The exercises focus on creating, accessing, modifying, and performing operations on different data structures, as well as applying conditional logic to solve basic programming tasks.

## 📌 Problem Statements

• Creating and working with Python Lists
• Modifying lists using built-in methods
• Accessing list elements using indexing and slicing
• Creating and manipulating Dictionaries
• Working with Sets and understanding unique elements
• Performing Union and Intersection operations
• Using Operators and Conditional Statements
• Applying if, elif, and else
• Taking user input using input()
• Using built-in functions such as min(), max(), and sum()

## 🐍 Topics Covered

### 1. Lists

Created and worked with age_list and name_list.

List operations practiced:

append()
insert()
remove()
pop()
extend()
sort()
min()
max()
sum()

Also practiced:

Positive and negative indexing
List slicing
Reversing a list

Example:

age_list = [24, 25, 27, 28, 29]

age_list.insert(2, 26)
age_list.extend([31, 30, 32])
age_list.sort(reverse=True)

### 2. Dictionaries

Created a student_marks dictionary to store student names and their marks.

Practiced:

Creating dictionaries
Accessing values using keys
Adding new key-value pairs
Updating existing values
Using:
keys()
values()
items()

Example:

student_marks = {
    "Kala": 78,
    "Mala": 89,
    "Sri": 98,
    "Vino": 56,
    "Raj": 65
}

student_marks["Janani"] = 80
student_marks["Kala"] = 82

### 3. Sets

Created a set and explored how sets handle duplicate values.

my_set = {'a', 'e', 'i', 'o', 'u', 'a', 'a', 'i'}

A set stores only unique elements, so duplicate values such as 'a' and 'i' are automatically removed.

I also practiced:

Creating sets
Understanding that sets do not support indexing
Union
Intersection

Example:

set1 = {1, 3, 5, 7, 9}
set2 = {2, 3, 5, 8, 10}

set1.union(set2)
set1.intersection(set2)

### 4. Operators & Conditional Statements

Created a Performance Category Program that accepts a score from 0 to 10 and categorizes the performance.

Score	Category
Greater than 7	Above Average
4 to 7	Average
Less than 4	Below Average

The program uses:

input()
int()
Comparison operators
Logical operators
if
elif
else

Example:

if Score >= 0 and Score <= 10:
    if Score > 7:
        print("Above Average")
    elif Score >= 4:
        print("Average")
    else:
        print("Below Average")
else:
    print("Your Score range should be between 0 to 10")
    
## 💡 Key Learnings

Lists are ordered and mutable, allowing elements to be added, removed, and modified.
Dictionaries store data as key-value pairs.
Sets contain unique elements and do not support indexing.
List slicing makes it easy to access a range of elements.
if, elif, and else help make decisions based on conditions.
Built-in functions such as min(), max(), and sum() simplify common operations.
Regular coding practice helps improve logical thinking and problem-solving skills.

## 🛠️ Tools & Technologies

Python
Jupyter Notebook / Google Colab
GitHub

## 📝 Conclusion

Through this practice, I gained a better understanding of how Python Lists, Dictionaries, and Sets are created and manipulated using different built-in methods and operations. I also practiced indexing, slicing, set operations, user input, comparison operators, and conditional statements to implement simple problem-solving programs. This project helped me apply Python concepts through hands-on coding exercises.

Learning → Practicing → Improving → Growing 🚀

## 📚 Future Learning

I plan to continue learning:
Loops
Functions
List Comprehensions
Exception Handling
File Handling
NumPy
Pandas
Matplotlib
Data Analysis with Python

## 👩‍💻 Author

**Shanthini**

**Aspiring Data Analyst**

**Skills:** Python | Data Structures | List Operations | Dictionary Operations | Set Operations | Conditional Operations 

## 📄 License

This project is created for educational and assignment purposes only.

## 🙏 Acknowledgments

I would like to thank:

- **Entri Elevate Course Support** for providing guidance and learning resources throughout this project.
- **Python Documentation** for valuable references and support in understanding Python syntax, string operations, and tuple concepts.
- **Google Colab** for providing an interactive environment to practice and execute Python code.

