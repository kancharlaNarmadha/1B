
# EX 10C Java List Interface
## DATE:
## AIM:
To write a Java program of swap two elements in a list. Swapping 1st(index 0) element with the 3rd(index 2) element.














## Algorithm

1.Import required classes and define the main class ListSwapExample.

2.Create an ArrayList and read its size and elements from the user using Scanner.

3.Display the list contents before swapping.

4.Swap the 1st and 3rd elements of the list using Collections.swap() if size ≥ 3.

5.Display the list contents after swapping.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
    

import java.util.*;

public class ListSwapExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        List<String> list = new ArrayList<>();
        
        int size = sc.nextInt();
        sc.nextLine(); 
        
        for (int i = 0; i < size; i++) {
            list.add(sc.nextLine());
        }

        System.out.println("Array list before Swap:");
        for (String item : list) {
            System.out.println(item);
        }

        if (list.size() >= 3) {
            Collections.swap(list, 0, 2);
        } else {
            System.out.println("Not enough elements to perform swap.");
        }

        System.out.println("Array list after swap:");
        for (String item : list) {
            System.out.println(item);
        }

        sc.close();
    }
}


      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/8450153b-fd92-4e14-996e-41048236c619)


## Result:
Thus, the program to implement a Java program using ArrayList and Collections.swap() to exchange elements has been successfully executed.


