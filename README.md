
# EX 3C StringBuilder and toString method in java
## DATE:
## AIM:
To write a java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder.







## Algorithm

1.Create a class StringReplaceExample and define the main() method to execute the program.

2.Use a Scanner object to read a string input from the user.

3.Create a StringBuilder object initialized with the input string.

4.Use the replace(beginIndex, endIndex, replacement) method on the StringBuilder to replace the substring from beginIndex to endIndex - 1 with "Java".

5.Print the updated string using System.out.println().








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.Scanner;

public class StringReplaceExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        String input = scanner.nextLine();
        
        String replacement = "Java";
        int beginIndex = 1;
        int endIndex = 3;
        
        StringBuilder sb = new StringBuilder(input);
        sb.replace(beginIndex, endIndex, replacement);
        
        System.out.println( sb.toString());
        
        scanner.close();
    }
}


    
```

## Output:
![image](https://github.com/user-attachments/assets/cb90e109-bb64-461b-ad84-61f7b025bc8e)


## Result:
The program successfully replaces a portion of the input string (from index 1 to 2) with the word "Java" using StringBuilder.replace(), and then displays the modified string.







