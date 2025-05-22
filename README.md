
# EX 5B  Tightly encapsulated class
## DATE:
## AIM:
To create a java program to display the reverse string and  use tightly encapsulated class. 















## Algorithm

1.Create a class SetAndGet with a private string variable s.

2.Define a method setrevstr(String s) to assign the input string to the variable s.

3.Define a method getrevstr() to reverse and print the string using a loop.

4.In the main() method, create an object of SetAndGet and read a string input using Scanner.

5.Call setrevstr() to store the string, and then call getrevstr() to display the reversed string.






## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.*;
public class SetAndGet {
private String s;

public void getrevstr() {
    
    for(int j=s.length();j>0;--j)
	{
	System.out.print(s.charAt(j-1)); 
	}
}
public void setrevstr(String s) {
 this.s =s;
}

public static void main(String args[]){
 Scanner sc=new Scanner(System.in);
 SetAndGet obj = new SetAndGet();
 String str=sc.nextLine();
 
 obj.setrevstr(str);
 
 obj.getrevstr();
}
}  


    
```

## Output:
![image](https://github.com/user-attachments/assets/a3c90560-6c5b-421d-930c-42a4f380ffd2)


## Result:
The program successfully demonstrates the use of getters and setters to reverse a string.
It takes a string as input, stores it using a setter, and prints its reverse using a getter-like method.
