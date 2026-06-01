# 🐍 Python Data Types + type() + isinstance() + Practice Programs

---

# 📦 What is a Data Type?

A data type defines what kind of value a variable stores.

### Examples:
- Number
- Text
- List
- True/False

---

# ⚡ Python is Dynamically Typed

Python automatically detects the data type.

You don’t need to declare types manually.

```python
name = "John"
age = 25

✔ Python understands:

name → string
age → integer
📊 Common Data Types in Python
🔢 Integer (int)

Whole numbers (no decimals)

x = 10
🔣 Float

Numbers with decimals

x = 4.5
🔤 String (str)

Text inside quotes

x = "hello"
✔ Boolean (bool)

True or False values

x = True
📋 List

Ordered collection (can mix types)

x = [1, "hello", 3.14, True]
📦 Tuple

Like list but cannot be changed

x = (1, "hello", 3.14)
🔑 Set

Unordered, unique values only

x = {1, 2, 3}
📘 Dictionary

Key-value pairs

x = {"name": "Alice", "age": 25}
🔁 Range

Sequence of numbers (used in loops)

x = range(5)
🚫 None

Represents no value

x = None
🧠 MCQ Answers (Data Types)
1. What is dynamic typing?

✔ Python automatically determines data type

2. Integer vs Float?

✔ int = whole numbers
✔ float = decimal numbers

3. True/False type?

✔ Boolean

🔍 type() Function

Used to check the data type of a variable.

developer = "Devin"
print(type(developer))

✔ Output:

<class 'str'>

⚠️ If you don’t pass a value → error

🧪 isinstance() Function

Used to check if a variable belongs to a type.

✔ Example 1
account_balance = "12"
print(isinstance(account_balance, int))

✔ Output:

False
✔ Example 2 (Multiple types)
account_balance = 12
print(isinstance(account_balance, (int, float)))

✔ Output:

True
⚡ Key Difference
type() → shows exact type
isinstance() → checks if type matches
🧠 MCQ Answers (type & isinstance)
1. Output:
developer = 'Devin'
print(type(developer))

✔ <class 'str'>

2. Function to check type?

✔ isinstance()

3. Output:
account_balance = 12
isinstance(account_balance, (int, float))

✔ True
