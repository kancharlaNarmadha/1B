
# EX 8B IO & FILE -READER/WRITER
## DATE:
## AIM:
To write a Java Program to read the content from the String using Reader

Note: Get the Input String from the User and Display the Content of the String using predefined function

 Initialize char[] array = new char[39];










## Algorithm


1.Import necessary classes from java.io.* and java.util.*.

2.Accept a string input from the user using Scanner.

3.Create a char[] array to store characters read from the input string.

4.Create a StringReader object and use the read() method to read characters into the array.

5.Print the content of the array and close the StringReader inside a try-catch block.






## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
    import java.io.*;  
    import java.util.*;
    public class JavaCharArrayReaderReadExample4 {  
       public static void main(String[] args) {  
    Scanner sc=new Scanner(System.in);
    String data=sc.nextLine();
   
    char[] array = new char[39];
    try {
      // Create a StringReader
      StringReader input = new StringReader(data);
      //Use the read method
      input.read(array);
      System.out.println("Data read from the string:");
      System.out.println(array);
      input.close();
    }
    catch(Exception e) {
      e.getStackTrace();
    }
       }  
    }  
               


    
```

## Output:
![image](https://github.com/user-attachments/assets/075296ab-a414-4845-aa21-56eb69cf1720)


## Result:
Thus, the program to implement a Java Program to read a byte in a file "testout.txt" using FileInputStream has been successfully executed.










