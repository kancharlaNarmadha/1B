
# EX 9B  BYTE ARRAY I/O
## DATE:
## AIM:
To write a java program to write common data into 2 files (F1.txt & F2.txt) using ByteArrayOutputStream

Note:

create two files F1.txt and F2.txt  Read the two Integer value from the user, Summation of two integer value should be in the F1.txt and F2.txt














## Algorithm

1.Create FileOutputStream objects for two files (F1.txt and F2.txt).

2.Create a ByteArrayOutputStream to hold output data in memory.

3.Read two integers from the user using Scanner and compute their sum.

4.Write the sum to the ByteArrayOutputStream and then to both files using writeTo().

5.Close the ByteArrayOutputStream and display a success message.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
  FileOutputStream fout=new FileOutputStream("F1.txt");
          FileOutputStream fout2=new FileOutputStream("F2.txt");
          ByteArrayOutputStream bout=new ByteArrayOutputStream();
          Scanner sc=new Scanner(System.in);
          int num=sc.nextInt();
          int num1=sc.nextInt();
          int num2=num+num1;
          bout.write(num2);
          bout.writeTo(fout);
          bout.writeTo(fout2);
          System.out.println("Success...");
          bout.close();

    

      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/3d80c890-6d96-4ee0-a17e-c14a1c066eda)


## Result:
Thus, the program to implement a Java program using ByteArrayOutputStream to write data to multiple files has been successfully executed.





