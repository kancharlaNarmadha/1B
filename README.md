
# EX 9C Java LinkedHashMap
## DATE:
## AIM:
To create a java program to create and add objects and display the map elements after replace key 100 for "java programming" in hashtable concepts not hashmap and then display one more time.












## Algorithm

1.Import required classes and define the main class Mapp.

2.Create a LinkedHashMap to store integer keys and string values with insertion order.

3.Read the size and key-value pairs from the user and insert them into the map using put().

4.Display the original entries using entrySet() and getKey()/getValue().

5.Replace the value for key 100 and display the updated map.










## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
    

import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  LinkedHashMap<Integer,String> map=new LinkedHashMap<>(); 
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
 map.replace(100,"welcome to java");
         
        System.out.println("HashMap After Replace :");
                 
        for(Map.Entry m:map.entrySet()){  
   System.out.println(m.getKey()+" "+m.getValue());  
  } 
 }  
}  
       
      
 
            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/fd549754-ea00-46a8-8d32-7ea5f3535176)


## Result:
Thus, the program to implement a Java program using LinkedHashMap to store, update, and display key-value pairs with insertion order has been successfully executed.


