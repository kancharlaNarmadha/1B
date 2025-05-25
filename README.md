
# EX 1E Java program using String Tokenizer
## DATE:
## AIM:
To write a java program using stringTokenizer to break a string based on multiple delimiters. Each character in the constructors delimiter field acts as one delimiter.

















## Algorithm

1.Start the program and create a Scanner object to take user input.

2.Read a string input from the user.

3.Create a StringTokenizer object with delimiters :, /, and ..

4.Use a loop to check if more tokens are available.

5.Print each token extracted by the tokenizer.






## Program:
```
Developed by: Kancharla Narmadha
Register Number: 212222110016
```



      
```
import java.util.Scanner;
import java.util.StringTokenizer;

public class MultiDelimiterTokenizer {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String input = sc.nextLine();

        StringTokenizer tokenizer = new StringTokenizer(input, ":/.");
        while (tokenizer.hasMoreTokens()) {
            System.out.println(tokenizer.nextToken());
        }
    }
}



            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/47be3d5c-ce59-4892-b94f-0339571e17e9)


## Result:
Thus, the program to implement a Java program using StringTokenizer with multiple delimiters to extract and display tokens has been successfully executed.













