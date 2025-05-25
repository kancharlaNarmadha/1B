
# EX 10A Java Collection FrameWork/Interfaces & Java ArrayList
## DATE:
## AIM:
To create an Array List to store n numbers (add elements of type Integer) and then display the n numbers.














## Algorithm

1.Import required classes and define the main class NumberList.

2.Use Scanner to read the number of elements from the user.

3.Create an ArrayList to store integer values.

4.Read integers from the user and add them to the list using add().

5.Iterate through the list using an enhanced for-loop and print each number.









## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
    

import java.util.ArrayList;
import java.util.Scanner;

public class NumberList {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        int n = scanner.nextInt();
        
        ArrayList<Integer> numbers = new ArrayList<>();
        
        for (int i = 0; i < n; i++) {
            int num = scanner.nextInt();
            numbers.add(num);
        }
        
        for (Integer number : numbers) {
            System.out.println(number);
        }
    }
}

      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/eb8f4246-b06f-4123-a2cd-b832c8d91bd4)


## Result:
Thus, the program to implement a Java program using ArrayList to store and display a list of numbers has been successfully executed.
