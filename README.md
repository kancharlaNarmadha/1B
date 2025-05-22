
# EX 4B Introduction to Inheritance
## DATE:
## AIM:
To write a Java program for below situation, Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.










## Algorithm

1.Create a class Name with three string variables: Fname, Mname, and Lname, and a method dispName() to display the full name.

2.Create a class Employee with an integer variable Emp_Id and an object of class Name.

3.Define the method dispName(int id) in the Employee class to assign and display the employee ID.

4.In the main() method, create an object of the Employee class.

5.Call the methods to display the employee ID and the full name by accessing the Name object inside the Employee object.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
class Name {
    String Fname;
    String Mname;
    String Lname;

    void dispName(String fn, String mn, String ln) {
        Fname = fn;
        Mname = mn;
        Lname = ln;
        System.out.println( Fname + " " + Mname + " " + Lname);
    }
}

class Employee {
    int Emp_Id;
    Name obj = new Name();

    void dispName(int id) {
        Emp_Id = id;
        System.out.println(Emp_Id);
    }
}

public class Main {
    public static void main(String[] args) {
        Employee emp = new Employee();
    
        emp.dispName(101);
       
        emp.obj.dispName("B", "Leo", "John");
    }
}


    
```

## Output:
![image](https://github.com/user-attachments/assets/751700fb-a49e-4bd6-9d41-cbb76ffb6dd0)


## Result:
The program successfully demonstrates composition in Java by using an object of one class (Name) inside another (Employee). It displays the employee ID and full name correctly.


