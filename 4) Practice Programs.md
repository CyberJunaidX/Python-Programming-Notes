````md id="python_datatypes_programs_solutions_clean_001"
# 🐍 Python Data Types – Practice Programs (With Solutions)

---

# 🟢 Level 1: Basic Data Types

## 1. Integer Practice
```python
x = 10
print(x)
````

---

## 2. Float Practice

```python
x = 4.5
print(x)
```

---

## 3. String Practice

```python
name = "Alex"
print(name)
```

---

## 4. Boolean Practice

```python
is_student = True
print(is_student)
```

---

# 🟡 Level 2: Multiple Data Types

## 5. Mixed Variables

```python
name = "Jordan"
age = 22
height = 5.8
is_active = True

print(name)
print(age)
print(height)
print(is_active)
```

---

## 6. Identify Data Types

```python
name = "Emily"
age = 19
height = 5.6

print(type(name))
print(type(age))
print(type(height))
```

---

## 7. Type Checking Practice

```python
x = "Python"
print(x, type(x))
```

---

# 🟠 Level 3: type() Function Practice

## 8. Identify Types

```python
x = 100
y = "100"
z = 100.0

print(type(x))
print(type(y))
print(type(z))
```

---

## 9. Compare Types

```python
a = "100"
b = 100

print(type(a))
print(type(b))
```

---

## 10. Multiple Type Output

```python
a = "Hello"
b = 42
c = 3.14

print(type(a), type(b), type(c))
```

---

# 🔵 Level 4: isinstance() Practice

## 11. Check Integer Type

```python
num = 27
print(isinstance(num, int))
```

---

## 12. Check String Type

```python
text = "Python"
print(isinstance(text, str))
```

---

## 13. Check Multiple Types

```python
value = 7.5
print(isinstance(value, (int, float)))
```

---

## 14. Invalid Type Check

```python
balance = "500"
print(isinstance(balance, int))
```

---

# 🔥 Level 5: Logic-Based Practice

## 15. Type Safety Check

```python
num = 15

if isinstance(num, int):
    print(num * 2)
else:
    print("Wrong type!")
```

---

## 16. Data Validation

```python
data = "123"

if isinstance(data, int):
    print("Valid integer")
else:
    print("Invalid type")
```

---

## 17. Type Display Program

```python
name = "Jordan"
age = 21
height = 5.7

print(name, type(name), isinstance(name, str))
print(age, type(age), isinstance(age, int))
print(height, type(height), isinstance(height, float))
```

---

# 🧠 Key Practice Summary

* Data types define the kind of value stored in a variable
* `type()` shows the exact data type
* `isinstance()` checks if a value belongs to a type
* Python automatically assigns data types
* Practice helps avoid type-related errors

---

```
```

