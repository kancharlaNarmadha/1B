
# EX 5D IS-A relationship and HAS-A relationship
## DATE:
## AIM:
To write a java program to print the addition of two numbers, read two values use class and objects.Apply the has-a relationship concepts.


Note:

read the input value in string format.














## Algorithm

1.Create a class add with a method sum(int a, int b) that returns the sum of two integers.

2.In the Main class, declare variables for input and result (a, b, s).

3.Use Scanner to take two integer inputs from the user.

4.Create an object of the add class and call the sum() method with the inputs.

5.Print the result of the addition returned by the sum() method.





## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.Scanner;
class add{
   int sum(int a, int b) {
        return (a + b);
    } 
}
public class Main {
    public static void main(String args[]) {
        int a, b, s;
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        b = sc.nextInt();
        add dd = new add();
        s = dd.sum(a, b);
        System.out.println("Sum is:" + s);
    }
}


    
```

## Output:
![image](https://github.com/user-attachments/assets/f0977395-0e95-47c1-81a9-f92558af1382)


## Result:
The program successfully reads two integers from the user, calculates their sum using a separate method in another class, and displays the result.


