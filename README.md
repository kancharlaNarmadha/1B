
# EX 9B Java Map, HashMap and HashTable
## DATE:
## AIM:
To create a java program to create and add objects  in hashmap interface.











## Algorithm

1.Import required classes and define the main class Mapp.

2.Create a HashMap to store integer keys and string values.

3.Read the size and map entries (key-value pairs) from the user using Scanner.

4.Insert each key-value pair into the HashMap using put().

5.Iterate over the map using entrySet() and display all key-value pairs.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
    

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  HashMap<Integer,String> map=new HashMap<Integer,String>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  }  
 }  
}  
       
      
 
            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/b9f6e829-70ea-4c31-9c76-5b025a12d33e)


## Result:
Thus, the program to implement a Java program using HashMap to store and display key-value pairs entered by the user has been successfully executed.

