
# EX 6C Hierarchical Inheritance & Multiple Inheritance
## DATE:
## AIM:
To write a Java Program for below Scenario.

Hierarchical Inheritance Example in Python

1. Media Class have constructor to display "Parent Class is Media"

2. Magazine Class constructor call its parent constructor and display "Magazine is the one of the Child of Media Class"

3. Channel Class constructor call its parent constructor and display "Channel is the one of the Child of Media Class"

4. In Main class create object for Child class and access its corresponding Constructor










## Algorithm

1.Create a parent class Media with a constructor that prints a message.

2.Create a subclass Magazine that calls the parent constructor using super() and prints its own message.

3.Create another subclass Channel that also calls the parent constructor and prints its own message.

4.In the main() method, create objects of Magazine and Channel classes.

5.Observe constructor calls showing how parent and child constructors are invoked in inheritance.




## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
class Media {
    Media() {
        System.out.println("Parent Class is Media");
    }
}

class Magazine extends Media {
    Magazine() {
        super();
        System.out.println("Magazine is the one of the Child of Media Class");
    }
}

class Channel extends Media {
    Channel() {
        super();
        System.out.println("Channel is the one of the Child of Media Class");
    }
}

public class prog {
    public static void main(String[] args) {
        Magazine mag = new Magazine();

        Channel ch = new Channel();
    }
}






    
```

## Output:
![image](https://github.com/user-attachments/assets/fcf41418-4ab8-4248-9686-e0780af9e9db)


## Result:
The program demonstrates constructor chaining in inheritance. When a child class object is created, the parent class constructor is called first, followed by the child class constructor. This happens for both Magazine and Channel objects.





