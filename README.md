
# EX 5C  Getter and Setter method
## DATE:
## AIM:
To create a java program to print the product of two number using getter and setter method.

Note:

read the input value in string format.














## Algorithm

1.Create a class SetAndGet with two private string variables a and b.

2.Define a method setadd(String a, String b) to assign values to a and b.

3.Define a method getadd() to convert the strings to integers and print their product.

4.In the main() method, take two string inputs using Scanner.

5.Call setadd() to store the values and getadd() to compute and display the product.






## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.*;
public class SetAndGet {
private String a;
private String b;

public void getadd() {
    int a1=Integer.parseInt(a);
    int b1=Integer.parseInt(b);
	System.out.print("Product is " + (a1*b1)); 
	
}
public void setadd(String a,String b) {
 this.a =a;
 this.b=b;
}

public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 String str=sc.nextLine();
 String str1=sc.nextLine();
 
 obj.setadd(str,str1);
 
 obj.getadd();
}
}


    
```

## Output:
![image](https://github.com/user-attachments/assets/c8a0cb50-c109-4794-bc25-85ea58d0cb2b)


## Result:
The program successfully demonstrates the use of getter and setter methods to read string inputs, convert them to integers, and print their product.

