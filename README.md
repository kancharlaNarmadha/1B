
# EX 8C FILTER INPUT/OUTPUT STREAMS
## DATE:
## AIM:
To write a Java Program to get the actual number of available bytes in the file using filter input stream.

Note:Already sample.txt file was created. Read the input from the user for read method










## Algorithm


1.Start the program by importing necessary classes and creating a FileInputStream to read from "sample.txt".

2.Wrap the FileInputStream in a BufferedInputStream to enable filtering and buffering features.

3.Use a Scanner to take user input for how many bytes to read.

4.Display the number of available bytes before and after reading the specified number of bytes using a for loop.

5.Close both streams (file1 and filter) properly to release system resources.






## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
         FileInputStream  file1 = new FileInputStream("sample.txt");  
        FilterInputStream filter = new BufferedInputStream(file1);  
        Scanner sc=new Scanner(System.in);
               int sk=sc.nextInt();
         System.out.println("Available bytes in the file: " +filter.available());
        for(int i=0;i<sk;i++)
        {
            filter.read();
        }
          System.out.println("Available bytes in the file: " +filter.available());
  file1.close();  
        filter.close();  
 
            
      
 
            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/ca93375b-f935-410c-b0f7-ab2e1353f590)


## Result:
Thus, the program to implement a Java Program using BufferedInputStream to check and read available bytes from a file "sample.txt" has been successfully executed.











