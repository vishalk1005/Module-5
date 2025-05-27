# Exp.No:22  
## Destructor

### AIM  
To create a Python class `Student` with a destructor.

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

### PROGRAM

```
class student:
    def __init__(self,name,age):
        self.name=name
        self.age=age
    def printDetail(self):
        print(f"My name is {self.name} and I am {self.age} years old. ")
    def __del__(self):
        print(f"{self.name} student is deleted.")
s1=student("Vishvajit Rao",22)
s1.printDetail()
del s1

```

### OUTPUT
![image](https://github.com/user-attachments/assets/9c4931e8-e5b3-4b3d-ba32-568739fbedb6)

### RESULT
Thus the program to create a Python class `Student` with a destructor has been implemented and executed successfully.
