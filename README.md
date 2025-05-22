
# EX 7C THREAD & THREAD GROUPS
## DATE:
## AIM:
To write a Java program to count the vowels and consonant in the given string by calling run method

Note: Get the value from the User










## Algorithm

1.Create a class VowelConsonantCounter that implements Runnable and receives a string input through the constructor.

2.Override the run() method to count vowels and consonants in the input string using a loop.

3.Use Character.isLetter() to ensure only letters are considered, and identify vowels using "aeiou".

4.In the main() method, read a string from the user using Scanner.

5.Create and start a Thread by passing an instance of VowelConsonantCounter to count vowels and consonants concurrently.






## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.Scanner;

class VowelConsonantCounter implements Runnable {
    String input;

    public VowelConsonantCounter(String input) {
        this.input = input;
    }

    public void run() {
        int vowels = 0, consonants = 0;
        input = input.toLowerCase();

        for (int i = 0; i < input.length(); i++) {
            char ch = input.charAt(i);

            if (Character.isLetter(ch)) {
                if ("aeiou".indexOf(ch) != -1) {
                    vowels++;
                } else {
                    consonants++;
                }
            }
        }

        System.out.println("Number of vowels: " + vowels);
        System.out.println("Number of consonants: " + consonants);
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String userInput = sc.nextLine();

        VowelConsonantCounter counter = new VowelConsonantCounter(userInput);
        Thread t = new Thread(counter);
        t.start();
    }
}



    
```

## Output:
![image](https://github.com/user-attachments/assets/264716fd-df19-4533-8e08-565ba950e1d8)


## Result:
The program successfully uses a thread to count and display the number of vowels and consonants in a user-given string.








