
# EX 8A IO-FILE- STREAMS
## DATE:
## AIM:
To implement a Java Program to read a byte in a file "testout.txt" using FileInputStream











## Algorithm


1.Import java.io.* package to work with file input streams.

2.Use FileInputStream to open a file named "testout.txt" for reading.

3.Read a character from the file using input.read() and store it in an integer variable.

4.Print the character read by converting the integer to a character using (char)i.

5.Close the stream using input.close() inside a try-catch block to handle exceptions.




## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
  try
             {
                FileInputStream input=new FileInputStream("testout.txt");
                
                int i=input.read();
            
                
                    System.out.println((char)i);
                    input.read();
                
                input.close();
                

               
  
                }
                catch(Exception e){System.out.println(e);}
               


    
```

## Output:
![image](https://github.com/user-attachments/assets/1c7dc877-9059-482b-9a2d-657b19893e01)


## Result:
Thus the program to implement a Java Program to read a byte in a file "testout.txt" using FileInputStream has been successfully executed









