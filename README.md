
# EX 9A  I/O-STREAM
## DATE:
## AIM:
To write a Java Program to read a boolean Value from a file "OutputFile.txt" using DataInputStream . Use Predefined Function read for reading

Note Initialize DataInputStream Object name as "di"














## Algorithm

1.Create a FileInputStream to read from the file OutputFile.txt.

2.Wrap the input stream with DataInputStream to enable reading primitive data types.

3.Read a boolean value from the file using readBoolean().

4.Print the boolean value to the console.

5.Close both FileInputStream and DataInputStream to release resources.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
 FileInputStream input = new FileInputStream("OutputFile.txt");  
    DataInputStream di = new DataInputStream(input);  
 
 boolean data =di.readBoolean();
   
      System.out.println(data);  
    input.close();
    di.close();
    

      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/4b663566-dcce-4671-a4d0-48e7191a34a5)


## Result:
Thus, the program to implement a Java program using DataInputStream to read a boolean value from a file has been successfully executed.




