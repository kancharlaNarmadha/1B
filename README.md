
# EX 3D StringTokenizer in java
## DATE:
## AIM:
To write a java program to print output upto separator symbol(,) based on input using nextToken method of the string tokenizer java.








## Algorithm

1.Create a class StringTokenizerExample and define the main() method to run the program.

2.Use a Scanner object to read a comma-separated string input from the user.

3.Create a StringTokenizer object using the input string and "," as the delimiter.

4.Check if there are tokens remaining using hasMoreTokens().

5.Print the next token using nextToken() if available.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.*;
public class StringTokenizerExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String input = scanner.nextLine();
        StringTokenizer tokenizer = new StringTokenizer(input, ",");
        if (tokenizer.hasMoreTokens()) {
            System.out.println("Next token is : " + tokenizer.nextToken());
        }
    }
}
    
```

## Output:
![image](https://github.com/user-attachments/assets/fbbbb9b2-e6e8-4d35-a373-81523565a96f)


## Result:
The program successfully reads a comma-separated string from the user and prints the first token using StringTokenizer.








