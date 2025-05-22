
# EX 2D Array as Argument
## DATE:
## AIM:
To write a java program to display elements of one dimensional array and passing 2d array value to function or methods. 





## Algorithm

1.Create a class TwoDArray with a method show(int[][] x) that accepts a 2D array as a parameter.

2.Inside the show() method, use nested for loops to iterate through the 2D array and print its elements in matrix form.

3.In the main() method of the PassingTwoDArrayToMethod class, declare and initialize a 2D array x.

4.Create an object of the TwoDArray class to call the show() method.

5.Call the show() method and pass the 2D array x to display its contents.








## Program:

Developed by: Kancharla Narmadha
Register Number: 212222110016
```
class TwoDArray 
{
 void show(int x[ ][ ])
 {
    int i, j;
    System.out.println("Matrix x: ");
   for(i = 0; i < x.length; i++)
   {
	 for(j = 0; j < x.length; j++)
	   System.out.print(x[i][j]+ " ");
	   System.out.println();
   }
  }
}
public class PassingTwoDArrayToMethod {
public static void main(String[] args) 
{
 int x[ ][ ] = {{1, 2},{3, 4}};
 TwoDArray obj = new TwoDArray();
  obj.show(x);
 }
}
    
```

## Output:
![image](https://github.com/user-attachments/assets/ef61b891-f505-4ab4-be0c-0ba75117f387)


## Result:
The program successfully demonstrates how to pass a two-dimensional array to a method in Java. It prints the elements of the matrix in a structured format.





