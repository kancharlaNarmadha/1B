
# EX 2B Access Modifier
## DATE:
## AIM:
To demonstrate the java program using public access modifier and to check Vowel or Consonant using Switch Case.




## Algorithm

1.Create a class VowelConsonantChecker with a method checkCharacter(char ch) to determine if a character is a vowel, consonant, or not a letter.

2.Convert the input character to uppercase using Character.toUpperCase(ch) to ensure case-insensitive checking.

3.Use Character.isLetter(ch) to check if the input is an alphabet character.

4.Use a switch statement to check if the character is a vowel (A, E, I, O, U) and print the result; otherwise, print it's a consonant.

5.In the main() method, read a character from the user, create an object of the class, and call the checkCharacter() method to display the result.




## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.Scanner;

public class VowelConsonantChecker { 

    public void checkCharacter(char ch) {
       
        ch = Character.toUpperCase(ch);

       
        if (Character.isLetter(ch)) {
            switch (ch) {
                case 'A':
                case 'E':
                case 'I':
                case 'O':
                case 'U':
                    System.out.println(ch + " is  a Vowel");
                    break;
                default:
                    System.out.println(ch + " is a Consonant");
            }
        } else {
            System.out.println("Input is not an alphabet");
        }
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

      
        char input = scanner.next().charAt(0);

       
        VowelConsonantChecker checker = new VowelConsonantChecker();
        checker.checkCharacter(input);

        scanner.close();
    }
}


```

## Output:
![image](https://github.com/user-attachments/assets/3426d9e4-2a33-4c58-8d7c-25e797dad2bc)


## Result:
The program successfully determines whether the given character is a vowel, consonant, or not an alphabet. It handles both uppercase and lowercase input correctly using built-in character-handling methods.



