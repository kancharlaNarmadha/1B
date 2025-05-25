
# EX 12C Java Stack & Vector
## DATE:
## AIM:
To write a java program to read and  print the  elements using vector in java collection.

Note:

Use addElement method().














## Algorithm

1.Create a Vector of strings to store user input.

2.Read initial elements from the user and add them using add().

3.Display the current contents of the vector.

4.Read more elements and add them using addElement().

5.Print the final updated vector.







## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.*;

public class VectorDemo {
	public static void main(String args[])
	{

		
		Vector<String> vec_tor = new Vector<String>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
	    for(int i=0;i<size;i++)
	    {
		vec_tor.add(sc.next());
	    vec_tor.add(sc.next());
	    }
	

		System.out.println("The vector is: " + vec_tor);

		int size1=sc.nextInt();
	    for(int j=0;j<size1;j++)
	    {
		vec_tor.addElement(sc.next());
	    }

	
		System.out.println("The new Vector is: " + vec_tor);
	}
}


      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/0bdf18ff-7cc7-4cb5-8787-7960cabfd8e5)


## Result:
Thus, the program to implement a Java program using Vector to add and display elements using both add() and addElement() has been successfully executed.











