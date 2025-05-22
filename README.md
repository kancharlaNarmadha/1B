
# EX 3B String Buffer in java
## DATE:
## AIM:
To write a java program to use delete() method of the StringBuffer class deletes the String from the specified beginIndex to endIndex.






## Algorithm

1.Create a class StringBufferExample4 and define the main() method to run the program.

2.Use a Scanner object to take input from the user: a string, followed by two integers representing start and end indices.

3.Create a StringBuffer object initialized with the input string.

4.Call the delete(startIndex, endIndex) method on the StringBuffer object to remove characters from startIndex to endIndex - 1.

5.Print the modified string using System.out.println().








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.Scanner;

public class StringBufferExample4 {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        
        String str1 = sc.nextLine();
        
        int startIndex = sc.nextInt();
        
        int endIndex = sc.nextInt();
        
        StringBuffer sb = new StringBuffer(str1);
        
        sb.delete(startIndex, endIndex);
         
        System.out.println(sb);
        
        sc.close();
    }
}

    
```

## Output:
![image](https://github.com/user-attachments/assets/4cbc487d-5e60-4c7f-81b6-1dc138549071)


## Result:
The program successfully removes the specified substring from the input string using the StringBuffer.delete() method and displays the updated string.






