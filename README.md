
# EX 6B Multi Level Inheritance
## DATE:
## AIM:
To create 3 classes Vehicle, Car and Alto. Class Alto extends Class Car and Class Car extends Class Vehicle.

Class Vehicle has display() and it displays “Vehicle Class”

Class Car has print() and displays “Car Class”

Class Alto has show() and displays “Alto Class"

In Main class create Object for Alto class and access all methods.










## Algorithm

1.Create a base class Vehicle with a method display() that prints "Vehicle Class".

2.Create a subclass Car that extends Vehicle and adds a method print() to print "Car Class".

3.Create a subclass Alto that extends Car and adds a method show() to print "Alto Class".

4.In the main() method, create an object of Alto.

5.Call all three methods (display(), print(), show()) on the Alto object to demonstrate multilevel inheritance.




## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
class Vehicle {
    void display() {
        System.out.println("Vehicle Class");
    }
}

class Car extends Vehicle {
    void print() {
        System.out.println("Car Class");
    }
}

class Alto extends Car {
    void show() {
        System.out.println("Alto Class");
    }
}

public class Main {
    public static void main(String[] args) {
        Alto obj = new Alto();
        obj.display();
        obj.print();
        obj.show();
    }
}



    
```

## Output:
![image](https://github.com/user-attachments/assets/4e48ad95-8b22-4f01-b948-9c7755cbbcf6)


## Result:
The program successfully demonstrates multilevel inheritance where the Alto class inherits methods from both Car and Vehicle classes, and all methods print their respective class names.




