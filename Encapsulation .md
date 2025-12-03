#  6b.Python OOP: Encapsulation with Private Members

##  AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

##  ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

##  Program
```
class Rectangle:
    def __init__(self,length,breadth):
        self.__length = length #private variable
        self.__breadth = breadth#private variable
    def display(self):
        print(self.__length)
        print(self.__breadth)
 
rect = Rectangle(5,3)
rect.display()

```

## Output
<img width="859" height="210" alt="image" src="https://github.com/user-attachments/assets/c4fdbb86-6cd5-46ee-b1a5-8c829fc66153" />


## Result
Thus the program to implement Encapsulation in Python by defining a class Rectangle with private member variables __length and __breadth is executed successfully
