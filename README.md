
# EX 9C STRING READER/WRITER
## DATE:
## AIM:
To write a Java Program to print the String value "Hi Everybody,Welcome to Java StringReader." Using StringReader















## Algorithm

1.Import required classes and define the main class StringReaderExample.

2.Create a string to be read using StringReader.

3.Initialize a StringReader with the input string.

4.Read characters one by one from the StringReader using a while loop.

5.Print each character to the console until the end of the string is reached.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
 import java.io.StringReader;  
public class StringReaderExample {  
    public static void main(String[] args) throws Exception {  
        String srg = "Hi Everybody,Welcome to Java StringReader.";  
        StringReader reader = new StringReader(srg);  
        int k=0;  
            while((k=reader.read())!=-1){  
                System.out.print((char)k);  
            }  
        }  
}  

      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/3330e00d-e8a6-4425-a9dc-fc2737153efe)


## Result:
Thus, the program to implement a Java program using StringReader to read and display characters from a string has been successfully executed.






