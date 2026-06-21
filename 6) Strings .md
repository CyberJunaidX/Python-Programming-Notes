# Strings and String Immutability 

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

