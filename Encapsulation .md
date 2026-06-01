# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```py
class Rectangle:
    def __init__(self, length, width):
        # private variables
        self.__length = length
        self.__width = width

    def display(self):
        # accessing private variables within the class
        print(self.__length)
        print(self.__width)

# create object
rect = Rectangle(5, 3)

# print values within the class
rect.display()
```

## Output
<img width="173" height="76" alt="image" src="https://github.com/user-attachments/assets/992da165-36f6-4de6-baba-881772e7d0fe" />

## Result
Thus , the program has been executed successfully.
