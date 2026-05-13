# 📚 String Library - C++ OOP

![C++](https://img.shields.io/badge/C%2B%2B-Programming-blue?logo=c%2B%2B)
![OOP](https://img.shields.io/badge/OOP-Design%20Principle-green)
![Algorithms](https://img.shields.io/badge/Algorithms-String%20Manipulation-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

A custom **C++ String Utility Library** implemented using **Object-Oriented Programming (OOP)** principles.

This library contains a collection of commonly used **string manipulation algorithms** organized inside a reusable class called `clsString`.

The goal of this project is to demonstrate how to transform algorithm-based functions into a **clean, reusable, and maintainable C++ library**.

---

# 📑 Table of Contents

- Project Overview
- Features
- Concepts Applied
- Project Structure
- Example Usage
- Example Output
- Future Improvements
- Learning Source

---

# 🚀 Project Overview

Working with strings is one of the most common tasks in programming.

Instead of rewriting string functions repeatedly, this project organizes many useful **string algorithms** into a single **reusable class library**.

The project demonstrates how **Object-Oriented Programming** can be used to design reusable components that improve code structure and maintainability.

---

# ⚙️ Features

The `clsString` class provides many useful utilities for working with strings.

## 📝 Word Operations

- Count words in a string
- Print each word
- Reverse words order
- Split string into words
- Join words into a string

## 🔤 Letter Operations

- Convert string to **Uppercase**
- Convert string to **Lowercase**
- Capitalize the **first letter of each word**
- Invert letter case
- Count **capital letters**
- Count **small letters**

## 🔍 Character Analysis

- Count specific characters
- Count vowels
- Print vowels in a string

## ✂️ String Cleaning

- Trim left spaces
- Trim right spaces
- Trim full string
- Remove punctuation

## 🔄 String Editing

- Replace words in a string
- Reverse words
- Modify characters

---

# 🧠 Concepts Applied

This project demonstrates several core programming concepts:

- Object-Oriented Programming (OOP)
- Encapsulation
- Function Overloading
- Static Methods
- Code Reusability
- Clean Code Practices
- Algorithm Implementation

---

# 📂 Project Structure

```
Project-8-String-Library-OOP
│
├── clsString.h
│   String utility class containing all string operations
│
└── main.cpp
    Example program demonstrating how to use the library

```

---

# 💻 Example Usage

```cpp
#include <iostream>
#include "clsString.h"
using namespace std;

int main()
{
    clsString String1("Ahmed Yaser");

    cout << "String1 = " << String1.Value << endl;

    cout << "Number of words: "
         << String1.CountWords() << endl;

    String1.UpperFirstLetterOfEachWord();

    cout << "After Capitalizing: "
         << String1.Value << endl;

    String1.ReverseWordsInString();

    cout << "Reversed Words: "
         << String1.Value << endl;

    String1.ReplaceWord("Ahmed", "Ibrahim");

    cout << "After Replace: "
         << String1.Value << endl;

    return 0;
}
```

---

# 🖥️ Example Output

```
String1 = Ahmed Yaser
Number of words: 2
After Capitalizing: Ahmed Yaser
Reversed Words: Yaser Ahmed
After Replace: Ibrahim Yaser
```

---

# 🎓 Learning Source

This project was implemented while following the **Programming Advices Roadmap**

Instructor  
**Dr. Mohammed Abu-Hadhoud**

The project demonstrates how to convert algorithm-based code into **clean and reusable object-oriented libraries**.

---
