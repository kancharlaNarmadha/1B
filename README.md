
# EX 9D SERILIZATION/DESERILIZATION
## DATE:
## AIM:
To write a Java program to perform transient in Student details(name,dept,rollno)

Note:

Student details are stored in a file "student.txt" using Serialization.

Create a class Studentinfo that implements Serializable interface to make its object serialized.

Initialize transient for dept,,rollno














## Algorithm

1.Define a class Studentinfo that implements the Serializable interface.

2.Declare data members: name as normal, and dept and rollno as transient.

3.Create a constructor to initialize all fields with user-provided values.

4.Assign values to name, dept, and rollno within the constructor.

5.Use transient to skip serialization of dept and rollno during object serialization.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
 class Studentinfo implements Serializable
{
    String name;
   transient String dept;
    transient int rollno;
   
    Studentinfo(String n, String r,int n1)
    {
    this.name = n;
    this.dept = r;
    this.rollno=n1;
    }
}

      


            
      
               


    
```

## Output:

![image](https://github.com/user-attachments/assets/3b215d7f-5262-4bda-bd1d-3182099e5bab)


## Result:
Thus, the class Studentinfo has been successfully created with transient fields that will not be serialized during the serialization process.







