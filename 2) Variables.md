````md id="python_full_notes_001"
# 🐍 Python Variables, Naming Conventions & print() Function – Full Notes

---

# 📦 Variables in Python

Variables are used to store data in memory.

- Variables store data
- Created using the assignment operator `=`
- No keywords like `let`, `var`, or `const` are needed

---

## 🧪 Example

```python
name = "John Doe"
age = 25
````

---

# ⚠️ Variable Naming Rules

## ✔ Rules

* Must start with a letter or underscore `_`
* Cannot start with a number
* Can contain:

  * Letters (a-z, A-Z)
  * Numbers (0-9)
  * Underscores `_`
* Variable names are **case-sensitive**

---

## 🧪 Example

```python
age = 10
Age = 20
AGE = 30
```

✔ These are all different variables

---

## ❌ Invalid Example

```python
5age = 25
```

✔ This gives:

```
SyntaxError
```

---

# 🐍 Naming Conventions

## 📌 Use snake_case

```python
user_age = 30
```

---

## 📌 Use descriptive names

✔ Better:

```python
user_age = 30
```

❌ Worse:

```python
ua = 30
```

---

## 📌 Avoid single-letter variables

❌ Bad:

```python
x = 56
```

✔ Reason: unclear meaning

---

# 💬 Comments in Python

Comments are used to explain code.

---

## 🟢 Single-line comment

```python
# This is a comment
```

---

## 🟡 Multi-line comment style

```python
# First line
# Second line
# Third line
```

---

# 🧠 Key Points

* Variables are created using `=`
* Use meaningful names
* Follow `snake_case` convention
* Avoid single-letter variables
* Comments help explain code

---

# 🧠 MCQ Answers (Variables)

## 1. Correct way to declare variable in Python:

✔ `age = 25`

---

## 2. NOT a rule for variables:

✔ Variable names are case-insensitive ❌
(Python is case-sensitive)

---

# 🖨️ Python print() Function

---

# 📌 What is print()?

`print()` is used to display output in the terminal.

It is a built-in function in Python.

---

## 🧪 Basic Example

```python
print("Hello world!")
```

---

## ✔ Output

```
Hello world!
```

---

# 📌 What is inside print()?

The value inside `print()` is called an **argument**.

```python
print("Hello world!")
```

---

# 🧾 Printing Multiple Values

```python
print("My favorite colors are", "blue", "green", "red")
```

---

## ✔ Output

```
My favorite colors are blue green red
```

---

# ⚙️ Key Behavior

* Commas `,` separate values
* Python automatically adds spaces between values

---

# 🧠 Key Points

* `print()` shows output in terminal
* Strings use `' '` or `" "`
* Multiple values → separated by commas
* Python automatically adds spaces

---

# 🧠 MCQ Answers (print)

## 1. Why does output have spaces?

✔ Because commas in `print()` add spaces automatically

---

## 2. Output of:

```python
print('Hello', 'world!')
```

✔ Output:

```
Hello world!
```

---

## 3. Purpose of quotation marks:

✔ They define a string for printing

---

```
```
