
# EX 4D Final ,Static Keyword
## DATE:
## AIM:
To write a Java program for below situation, Student object contains member 'Stu_Id'. It contains object named course, which contains its own informations such as Degree, Branch, Year of Studying.













## Algorithm

1.Create a class Course with variables degree, branch, and year, and a method dispCourse() to display course details.

2.Create a class Student with a variable Stu_Id and a Course object as a data member.

3.Define the method disp() in Student to initialize student ID and call dispCourse() using the Course object.

4.In the main() method, create a Student object and call disp() with student and course details.

5.Display the student ID and course details using the respective methods.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
class Course {
    String degree;
    String branch;
    String year;

    void dispCourse(String deg, String br, String yr) {
        degree = deg;
        branch = br;
        year = yr;
        System.out.println(degree + " " + branch + " " + yr);
    }
}

class Student {
    int Stu_Id;
    Course course = new Course();

    void disp(int id, String deg, String br, String yr) {
        Stu_Id = id;
        System.out.println(Stu_Id);
        course.dispCourse(deg, br, yr);
    }
}

public class Main {
    public static void main(String[] args) {
        Student s1 = new Student();
        s1.disp(101, "B.Tech", "IT", "Third year");
    }
}

    
```

## Output:
![image](https://github.com/user-attachments/assets/fcc49d46-fd09-47d7-989d-2e31748a8c1f)


## Result:
The program successfully demonstrates composition in Java, where a Student object contains a Course object, and both student ID and course details are displayed properly.




