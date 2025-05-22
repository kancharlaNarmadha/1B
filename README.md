
# EX 7B EXCEPTION HANDLING (Finally block- Throw-Throws- Final vs Finally vs Finalize)
## DATE:
## AIM:
To write a Java program to demonstrate control flow of try-catch-finally clause when ArrayIndexOutOfBoundsException occur in try block and handled in catch block











## Algorithm

1.Create an integer array arr with size 4 (indexes 0 to 3).

2.Use a try block to access an invalid index (arr[4]), which causes an ArrayIndexOutOfBoundsException.

3.Handle the exception using a catch block that catches and prints a message when the exception occurs.

4.Use a finally block to print a message indicating it always executes, regardless of whether an exception occurs.

5.Print a final message outside the try-catch-finally structure to confirm program flow continues.






## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
public class HelloWorld {
    public static void main(String[] args) {
        int[] arr = new int[4];

        try {
            int i = arr[4];
            System.out.println("Inside try block");
        } catch (ArrayIndexOutOfBoundsException ex) {
            System.out.println("Exception caught in catch block");
        } finally {
            System.out.println("finally block executed");
        }

        System.out.println("Outside try-catch-finally clause");
    }
}



    
```

## Output:
![image](https://github.com/user-attachments/assets/4cbac128-dcdc-40f4-b031-4c2ded52aedd)


## Result:
The program successfully demonstrates exception handling using try-catch-finally. The catch block handles the array index error, and the finally block executes unconditionally.







