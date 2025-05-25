
# EX 10B Java Linked List
## DATE:
## AIM:
To apply the getFirst() method in LinkedList java concepts.Create a linkedlist, read size of the list , read the elements for the linkedlist and display the first index of the element from the linkedlist.













## Algorithm

1.Import required classes and define the main class Main.

2.Create a LinkedList to store string elements (car names).

3.Read the number of elements from the user using Scanner.

4.Add each input string to the LinkedList using add().

5.Display the first element of the linked list using getFirst().










## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
    

import java.util.*;

public class Main {
  public static void main(String[] args) {
   Scanner sc=new Scanner(System.in);
    LinkedList<String> cars = new LinkedList<String>();
    int n=sc.nextInt();
    for(int i=0;i<n;i++)
    {
    cars.add(sc.next());
    }
    
    System.out.println("First Element :" + cars.getFirst());
  }
}

      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/111a0856-2ff4-402a-9890-083a020b335b)


## Result:
Thus, the program to implement a Java program using LinkedList to store and retrieve the first element has been successfully executed.

