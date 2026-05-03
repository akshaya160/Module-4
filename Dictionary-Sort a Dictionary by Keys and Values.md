# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
dict1 = {
    "a": 1,
    "b": 2,
    "c": 3
}
print(dict1)
sort = sorted(dict1.items())
print(sort)
sorted1 = sorted(dict1.items(),key=lambda item: item[1])
new = dict(sorted1)
print(new)
```

## Sample Output
<img width="356" height="99" alt="image" src="https://github.com/user-attachments/assets/352e5b55-7dcb-498f-895c-f570ed753d0c" />
## Result
Thus , a Python program that sorts a dictionary's:

Keys in alphabetical order
Values in alphabetical order is successfully executed.


## Result

