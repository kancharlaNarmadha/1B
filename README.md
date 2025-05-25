
# EX 10D Java HashSet & LinkedHashSet
## DATE:
## AIM:
To write a java program use hashset concepts in collection and add the elements to the hashset and then display the elements iterate(use while)and ignore the duplicate elements in hashset.















## Algorithm

1.Import required classes and define the main class HashSetDemo.

2.Create a HashSet to store unique string elements.

3.Read n strings from the user and add them to the set using add().

4.Create an Iterator to traverse the HashSet.

5.Use a while loop with the iterator to display each element in the set.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.*;

public class HashSetDemo{

public static void main(String args[]){

HashSet <String> hs = new HashSet <String>();
Scanner sc=new Scanner(System.in);
int n=sc.nextInt();
for(int i=0;i<n;i++)
{
    
hs.add(sc.next());

}
 Iterator<String> i=hs.iterator();  
 while(i.hasNext())  
 {  
    System.out.println(i.next());  
 }  

}
}


      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/04367cd4-921e-4ed0-ba34-b1aa33eded3e)


## Result:
Thus, the program to implement a Java program using HashSet and Iterator to store and display unique elements has been successfully executed.



