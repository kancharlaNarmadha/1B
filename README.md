
# EX 8D BUFFERED INPUT/OUTPUT STREAMS
## DATE:
## AIM:
To write a Java Program to read student data (name ,department, rollno) from the user using the BufferedReader class.

Consider Student Class using default constructor and instance method for displaying Student name, department, rollno







## Algorithm


1.Start the program by importing BufferedReader, InputStreamReader, and required classes.

2.Use BufferedReader to read name, department, and roll number from the user via console.

3.Create a Student object using the constructor with the collected input data.

4.Define and call the displayDetails() method to print the student’s information.

5.Successfully display the details of the student to the console.






## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
      import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
class Student{
String name;
int rollno;
String dept;
Student(String name, String dept, int rollno){
this.name = name;
this.dept = dept;
this.rollno = rollno;
}
public void displayDetails(){
System.out.println("Name: "+this.name);
System.out.println("Department: "+this.dept);
System.out.println("Rollno: "+this.rollno);
}
}
public class ReadData {
public static void main(String args[]) throws IOException {
BufferedReader reader =new BufferedReader(new InputStreamReader(System.in));

String name = reader.readLine();

String dept = reader.readLine();

int rollno = Integer.parseInt(reader.readLine());
Student std = new Student(name, dept, rollno);
std.displayDetails();
}
}
 
            
      
 
            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/326d4af7-19c5-48aa-af00-19a92480a395)


## Result:
Thus, the program to implement a Java Program using BufferedReader to read data from the user and display student details has been successfully executed.












