
# EX 2C Array
## DATE:
## AIM:
 To write a Java program that creates integer array of  size is 'n' elements, accepts values of arrays and find sum of all odd numbers in an array.




## Algorithm

1.Start the program with the class ss and define the main() method.

2.Use a Scanner object to take the array size and array elements as input from the user.

3.Store the elements in an integer array using a for loop.

4.Check each element for oddness using the condition Arr[j] % 2 != 0, and add the odd values to sumOdd.

5.Display the sum of all odd numbers using System.out.println().






## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
import java.util.*; 
public class ss
{
    public static void main(String[] args) 
    { 
        Scanner sc = new Scanner(System.in); 
        int size=sc.nextInt();
        int sumOdd=0;
        int Arr[] = new int[size]; 
        for(int i = 0; i < Arr.length; i++) 
           Arr[i] = sc.nextInt(); 
        for(int j = 0; j < Arr.length; j++){ 
           if(Arr[j]%2!=0){ 
             sumOdd = sumOdd + Arr[j];
           }
        }
        System.out.println("Sum of odd numbers: "+sumOdd); 
   } 
}
    
```

## Output:
![image](https://github.com/user-attachments/assets/b12e5857-4ca9-4d43-a619-240490c5976c)


## Result:
The program successfully accepts an array of integers from the user and calculates the sum of all odd numbers in the array. It then displays the correct result on the screen.




