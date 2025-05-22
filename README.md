
# EX 1C Control Statements
## DATE:
## AIM:
To write  a Java program to solve the following equation ,  y = x3 - 2 (x-3)3 + 20



## Algorithm

1.Start the program with the main class and define the main() method.

2.Create a Scanner object to take integer input from the user.

3.Read an integer x from the user using sc.nextInt().

4.Evaluate the expression x³ - 2(x - 3)³ + 20 using Math.pow() and store the result in variable y.

5.Print the result using System.out.println() to display the calculated value of y.




## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.Scanner;
public class main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int x=sc.nextInt();
        int y = (int)(Math.pow(x, 3) - 2 * Math.pow(x - 3, 3) + 20);
        System.out.println("value: "+y);
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/af2d7ba2-75a1-4c7a-ba76-a4071226772c)


## Result:
The program successfully accepts an integer input from the user and evaluates the expression x³ - 2(x - 3)³ + 20. It then displays the correct result on the screen.

