
# EX 9A Java TreeSet
## DATE:
## AIM:
To write a java program tailset start from the 15(Integer) , use the tailSet() method of SortedSet interface in Java is used to return a view of the portion of this set whose elements are greater than or equal to the parameter fromElement.









## Algorithm


1.Import BufferedReader, InputStreamReader, and necessary I/O classes.

2.Read the student’s name, department, and roll number from the console using BufferedReader.

3.Create a Student object using the input values through a constructor.

4.Call the displayDetails() method to show the student’s information.

5.Display the student’s details successfully on the console.






## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
    

import java.util.Scanner;
import java.util.SortedSet;
import java.util.TreeSet;

public class TailSetExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        TreeSet<Integer> treeSet = new TreeSet<>();

      
        int size = scanner.nextInt();

        for (int i = 0; i < size; i++) {
            int num = scanner.nextInt();
            treeSet.add(num);
        }

        SortedSet<Integer> tailSet = treeSet.tailSet(15);

        System.out.println("Elements greater than or equal to in set are : " + tailSet);

        scanner.close();
    }
}
            
      
 
            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/ff70a51c-ed8f-47e8-875e-6d27371cf460)


## Result:
Thus, the program to implement a Java program using TreeSet and tailSet() method to display all elements greater than or equal to a specific value has been successfully executed.
