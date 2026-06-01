# 🐍 Python Data Types – Short Notes

---

# 📦 What is a Data Type?

A data type defines the type of value stored in a variable.

### Examples:
- Number
- Text
- List
- True / False values

---

# ⚡ Python is Dynamically Typed

Python automatically detects the data type of a variable.

You do NOT need to declare the type manually.

### Example idea:
- If value is text → Python treats it as string
- If value is number → Python treats it as integer or float

---

# 📊 Common Data Types in Python

---

## 🔢 Integer (int)
Whole numbers without decimals.

Example: 10, 25, -5

---

## 🔣 Float
Numbers with decimal points.

Example: 4.5, 3.14, -0.8

---

## 🔤 String (str)
Text written inside quotes.

Example: "hello", "Python"

---

## ✔ Boolean (bool)
Represents True or False values.

Example: True, False

---

## 📋 List
Ordered collection of items.
Can store different data types together.

Example idea:
- Numbers + text + boolean together

---

## 📦 Tuple
Similar to a list but cannot be changed after creation.

---

## 🔑 Set
Unordered collection of unique values (no duplicates allowed).

---

## 📘 Dictionary
Stores data in key-value pairs.

Example idea:
- name → "Alice"
- age → 25

---

## 🔁 Range
Represents a sequence of numbers.
Commonly used in loops.

---

## 🚫 None
Represents absence of value (nothing stored).

---

# ⚡ Python is Dynamically Typed (Key Idea)

- Python decides the type automatically
- No need to declare types manually
- Type can be known only at runtime

---

# 🔍 type() Function

- Used to check the type of a variable
- Returns the class/type of value

### Key point:
- If no value is passed → error occurs

---

# 🧪 isinstance() Function

- Used to check whether a variable belongs to a specific type
- Returns:
  - True → if correct type
  - False → if not

---

### Example idea:
- Check if a value is an integer
- Check if a value is string or number
- Can also check multiple types together

---

# ⚡ Difference Between type() and isinstance()

- type() → tells the exact type of a value
- isinstance() → checks if value belongs to a type (or group of types)

---

# 🧠 Key MCQ Concepts

---

## ✔ Dynamic Typing
Python automatically assigns data types.

---

## ✔ Integer vs Float
- Integer → whole numbers
- Float → decimal numbers

---

## ✔ Boolean Type
Only contains:
- True
- False

---

## ✔ Type Checking
- type() → shows exact type
- isinstance() → verifies type condition

---

# 📌 Important Summary

- Python has many built-in data types
- It is dynamically typed
- type() and isinstance() are used for type checking
- Each data type has a specific purpose
- Understanding data types is essential for programming logic

---
