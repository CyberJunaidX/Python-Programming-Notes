# (1) Strings and String Immutability 

## What is a String?
- A string is a sequence of characters surrounded by single (' ') or double (" ") quotes.
- In Python, both are treated the same.

```python
my_str_1 = 'Hello'
my_str_2 = "World"
````

## Multiline Strings

* Use triple quotes for multiline strings.

```python
my_str_3 = """Multiline
string"""

my_str_4 = '''Another
multiline
string'''
```

## Strings with Quotes Inside

### 1. Use opposite quotes

```python
msg = "It's a sunny day"
quote = 'She said, "Hello World!"'
```

### 2. Use escape character ()

```python
msg = 'It\'s a sunny day'
quote = "She said, \"Hello!\""
```

## Checking Characters in a String (in operator)

* Returns True or False.

```python
my_str = 'Hello world'

print('Hello' in my_str)  # True
print('hey' in my_str)    # False
print('hi' in my_str)     # False
print('e' in my_str)      # True
print('f' in my_str)      # False
```

## Length of a String

* Use len() function.

```python
my_str = 'Hello world'
print(len(my_str))  # 11
```

## Indexing in Strings

* Index starts from 0.
* First character is index 0.

```python
my_str = "Hello world"

print(my_str[0])  # H
print(my_str[6])  # w
```

## Negative Indexing

* -1 gives last character.

```python
my_str = 'Hello world'
print(my_str[-1])  # d
print(my_str[-2])  # l
```

## String Immutability

* Strings cannot be changed after creation.
* You can reassign a variable, but cannot modify the string itself.

```python
greeting = 'hi'
greeting = 'hello'
print(greeting)  # hello
```

### ❌ Not Allowed:

```python
greeting = 'hi'
greeting[0] = 'H'  # TypeError
```

## Other Immutable Data Types

* integer
* float
* boolean
* tuple
* range

```
```

# (2) String Concatenation and String Interpolation

## String Concatenation
- Combining strings using the `+` operator.

```python id="c1m9kq"
my_str_1 = 'Hello'
my_str_2 = "World"

result = my_str_1 + ' ' + my_str_2
print(result)  # Hello World
````

## Important Rule

* You can only concatenate strings with strings.
* Mixing string + number causes an error.

```python id="k4n9zp"
name = 'John Doe'
age = 26

# print(name + age)  ❌ TypeError
```

## Converting to String (str())

* Use `str()` to convert numbers into strings.

```python id="p9x2ld"
name = 'John Doe'
age = 26

result = name + str(age)
print(result)  # John Doe26
```

## Augmented Assignment (+=)

* Shortcut for concatenation + assignment.

```python id="t7q1mv"
name = 'John Doe'
age = 26

name_and_age = name
name_and_age += str(age)

print(name_and_age)  # John Doe26
```

## String Interpolation (f-strings)

* Used to insert variables inside strings.
* Starts with `f` before quotes.
* Uses `{}` for variables or expressions.

```python id="r5v8ab"
name = 'John Doe'
age = 26

print(f"My name is {name} and I am {age} years old")
```

## Expressions inside f-strings

```python id="z3m8qf"
num1 = 5
num2 = 10

print(f"The sum of {num1} and {num2} is {num1 + num2}")
```

## Key Points

* No need to use `str()` inside f-strings.
* Python automatically converts values during interpolation.



# (3) String Slicing in Python 

## What is String Slicing?
- String slicing is used to extract a part of a string.

```python id="s1"
string[start:stop]
````

## Basic Example

```python id="s2"
my_str = "Hello world"
print(my_str[1:4])  # ell
```

* `start` is included
* `stop` is NOT included

---

## Omitting Start or Stop

### Omit start (starts from 0)

```python id="s3"
my_str = "Hello world"
print(my_str[:7])  # Hello w
```

### Omit stop (goes to end)

```python id="s4"
my_str = "Hello world"
print(my_str[8:])  # rld
```

### Omit both (whole string)

```python id="s5"
my_str = "Hello world"
print(my_str[:])  # Hello world
```

---

## Important Rule

* Slicing does NOT change the original string

```python id="s6"
my_str = "Hello world"
print(my_str[8:])  # rld
print(my_str)      # Hello world
```

---

## Step Parameter

```python id="s7"
string[start:stop:step]
```

* Controls how many characters to skip

### Example (step = 2)

```python id="s8"
my_str = "Hello world"
print(my_str[0:11:2])  # Hlowrd
```

---

## Reverse String

* Use step = -1

```python id="s9"
my_str = "Hello world"
print(my_str[::-1])  # dlrow olleH
```

---

## Key Points

* Square brackets are used for slicing
* `start` is included, `stop` is excluded
* Strings are immutable


# (4) Common String Methods in Python 

## 1. upper()
- Converts all characters to uppercase

```python id="m1"
my_str = "hello world"
print(my_str.upper())  # HELLO WORLD
````

---

## 2. lower()

* Converts all characters to lowercase

```python id="m2"
my_str = "Hello World"
print(my_str.lower())  # hello world
```

---

## 3. strip()

* Removes leading and trailing spaces (or characters)

```python id="m3"
my_str = "  hello world  "
print(my_str.strip())  # hello world
```

---

## 4. replace(old, new)

* Replaces part of a string

```python id="m4"
my_str = "hello world"
print(my_str.replace("hello", "hi"))  # hi world
```

---

## 5. split()

* Splits string into a list

```python id="m5"
my_str = "hello world"
print(my_str.split())  # ['hello', 'world']
```

---

## 6. join()

* Joins list into a string

```python id="m6"
my_list = ["hello", "world"]
print(" ".join(my_list))  # hello world
```

---

## 7. startswith()

* Checks if string starts with a value

```python id="m7"
my_str = "hello world"
print(my_str.startswith("hello"))  # True
```

---

## 8. endswith()

* Checks if string ends with a value

```python id="m8"
my_str = "hello world"
print(my_str.endswith("world"))  # True
```

---

## 9. find()

* Returns index of first occurrence
* Returns -1 if not found

```python id="m9"
my_str = "hello world"
print(my_str.find("world"))  # 6
```

---

## 10. count()

* Counts occurrences of substring

```python id="m10"
my_str = "hello world"
print(my_str.count("o"))  # 2
```

---

## 11. capitalize()

* First letter uppercase, rest lowercase

```python id="m11"
my_str = "hello world"
print(my_str.capitalize())  # Hello world
```

---

## 12. isupper()

* Checks if all letters are uppercase

```python id="m12"
my_str = "HELLO"
print(my_str.isupper())  # True
```

---

## 13. islower()

* Checks if all letters are lowercase

```python id="m13"
my_str = "hello"
print(my_str.islower())  # True
```

---

## 14. title()

* Capitalizes first letter of each word

```python id="m14"
my_str = "hello world"
print(my_str.title())  # Hello World
```

```




