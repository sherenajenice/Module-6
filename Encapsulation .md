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
class Rectangle:
    
    def __init__(self, length, width):
       
        self.__length = length  
        
        self.__width = width

r = Rectangle(5, 3)

print(r._Rectangle__length)

print(r._Rectangle__width)

## Output
<img width="206" height="96" alt="image" src="https://github.com/user-attachments/assets/001791c5-edaa-4ec8-9b6a-2d01a793f064" />

## Result
Thus, To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth` is verified.
