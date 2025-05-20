# Polymorphism And Its Functions

## AIM:
To Create a parent class Fish and define a class method type, then create a child class called Shark while overriding the type method so that objects instantiated from the Shark class use the overridden method.

## ALGORITHM:
1. Start

2. Define a class named Fish

    Create a method type() that prints "fish"

3. Define a subclass named Shark that inherits from Fish

    Override the type() method to print "shark"

4. Create an object obj_goldfish of class Fish

5. Create another object obj_hammerhead of class Shark

6. Call the type() method using obj_goldfish

    Output: "fish"

7. Call the type() method using obj_hammerhead

    Output: "shark" (because method is overridden in subclass)

8. End.

## PROGRAM:
```
Developed by: Naveenkumar M
Reg No: 212224230182

class Fish:
    def type(self):
        print("fish")

class Shark(Fish):
    def type(self):
        print("shark")

obj_goldfish=Fish()
obj_hammerhead=Shark()

obj_goldfish.type()
obj_hammerhead.type()

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/f0cc85bd-499f-4978-a940-1457ee417be2)

## RESULT:
The expected output is successfully executed.
