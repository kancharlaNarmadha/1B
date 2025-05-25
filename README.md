
# EX 9D Related to Map Concept
## DATE:
## AIM:
To create a java program to retrieve the key and value from map for all input value.

Note:

iterate over map using while loop.











## Algorithm

1.Import required classes and define the main class Mapp.

2.Create a HashMap to store integer keys and string values.

3.Read the size and user input, then insert key-value pairs into the map using put().

4.Create an iterator for the key set of the map.

5.Iterate through the map using the iterator and print each key-value pair.









## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
    

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  Map<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }




 }  
}  

      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/1d3b8829-26a1-4de7-ab79-75cb9dc0d35e)


## Result:
Thus, the program to implement a Java program using HashMap and Iterator to traverse and display key-value pairs has been successfully executed.



