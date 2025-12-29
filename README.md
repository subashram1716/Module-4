## PYTHON PROGRAMING MODULE 4
# Date: 06/12/2025

# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math as m
class pen:
    def stationary(self,a):
        self.a=a
    def f(self):
        print(f"Area of circle: {self.a*self.a*m.pi:.2f}")
d=int(input())
s=pen()
s.stationary(d)
s.f()
```

## Output

![502981549-975e2f70-7c72-4b8d-86dc-382ac6900914](https://github.com/user-attachments/assets/771aa9e3-4926-4c21-9335-3d21557a50ef)

## Result
The program successfully calculates the area of a circle using classes and objects.


## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1=eval(input())
dict2=eval(input())
dict1.update(dict2)
print(dict1)
```
## Output

![502981674-d603307a-15dd-413f-be8d-3a1edb7e5da6](https://github.com/user-attachments/assets/938c9ab2-1d9a-4e06-8bf3-24ca9b5e1ca1)

## Result
The program successfully merges two dictionaries. All key-value pairs from both dictionaries are combined. If a key exists in both dictionaries (like 'b'), the value from the second dictionary (dict2) overwrites the value from the first dictionary (dict1).


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
d={1:2, 5:12, 6:18, 4:24, 2:56, 3:323}
sorted_items=sorted(d.items(), key=lambda x: x[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_items)
```

## Sample Output

![502981851-043854a7-10b5-4206-a7fa-e34040fd3a4a](https://github.com/user-attachments/assets/55b803b1-8052-4add-a754-ffce434e5d29)

## Result
The program successfully sorts a dictionary.


# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
lst=[5, 10, 20]

try:
    print(lst[5])
except IndexError:
   print("You're out of list range")
```

## Output

![502981987-bdffc442-6460-46a2-872a-e72153188b20](https://github.com/user-attachments/assets/803eeb28-f645-44e3-a140-e1b46a6e3a60)


## Result
The program successfully handles an IndexError when attempting to access a list element beyond its range. Instead of crashing, it prints a custom message, informing the user that the requested index is out of range.


# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)
def print_lines_with_substring(file_path, substring):
    with open(file_path,'r') as file:
        for line in file:
            if substring in line:
                print(line.strip())
```

## Output

![502982086-e09b5b09-bb61-4213-b59a-ce087bb41fe1](https://github.com/user-attachments/assets/9bc1d663-4234-4e02-a118-e421bd696663)

## Result
The program successfully counts the number of lines in text file
