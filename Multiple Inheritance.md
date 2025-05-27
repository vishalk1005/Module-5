# Exp.No:23  
## SEB - Destructor

### AIM  
To write a Python program that demonstrates the use of a destructor method (__del__) in a class to indicate when an object is destroyed.

### ALGORITHM

1. Start the program.
2. Create a class named Demo.
3. Define the constructor __init__() to set an initial status.
4. Define the destructor __del__() to print a message when the object is deleted.
5. Create an object of the class Demo.
6. Print the object's status.
7. End of program (object is deleted automatically or with del obj).

### PROGRAM

```
class Demo:
    def __init__(self):
        self.status = "Alive"
    def __del__(self):
        print('The object no longer exists')
obj = Demo()
print(obj.status)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/d6201011-d512-457a-acbb-17db8110053d)


### RESULT
Thus the program that demonstrates the use of a destructor method (__del__) in a class to indicate when an object is destroyed has been implemented and executed successfully.
