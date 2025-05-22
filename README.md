
# EX 1D User Defined Method
## DATE:
## AIM:
To write a Java program to print Student details (Name,Collegename) cge_name is same to all members in the class. Use static type variable to access age.




## Algorithm

1.Define a class Main with a static variable cge_name and a non-static variable name.

2.Create the main() method to execute the program and accept user input using a Scanner.

3.Create two objects (obj1 and obj2) of the Main class.

4.Read names for both students using the Scanner and store them in obj1.name and obj2.name.

5.Display each student's name along with the static college name using System.out.println().




## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.*;
public class Main
{
    static String cge_name="SEC";
    String name;
	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	Main obj1=new Main();
	Main obj2=new Main();
	obj1.name=sc.next();
	obj2.name=sc.next();
	System.out.println("Student name: "+obj1.name+" College Name: "+cge_name);
	System.out.println("Student name: "+obj2.name+" College Name: "+cge_name);
	}
}

```

## Output:
![image](https://github.com/user-attachments/assets/485da226-4eac-496f-b418-b44fb50cd602)


## Result:
The program successfully demonstrates the use of static and non-static variables in Java. It takes two student names as input, stores them in separate objects, and displays each name along with the shared static college name.


