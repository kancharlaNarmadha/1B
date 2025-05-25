
# EX 12D Queue(Priority Queue) and Deque(Array Deque)
## DATE:
## AIM:
To write a java program to display the added elements from the Priority Queue.
















## Algorithm

1.Create a PriorityQueue of integers to store input numbers.

2.Read the number of elements from the user.

3.Add each input integer to the priority queue using add().

4.Display the contents of the priority queue.

5.Close the scanner (optional but good practice).







## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016



      
```
import java.util.*;

public class PriorityQueueDemo {
	

	public static void main(String args[])
	{
	
		PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        pQueue.add(sc.nextInt());
	    }
	    System.out.println("Display the element of Queue:");
		System.out.println(pQueue);

		
	}
}


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/47be3d5c-ce59-4892-b94f-0339571e17e9)


## Result:
Thus, the program to implement a Java program using PriorityQueue to insert and display elements has been successfully executed.












