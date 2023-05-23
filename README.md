## Experiment 1: Arithmetic Operations
### AIM:
To write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

### ALGORITHM:
Step 1:
Create the main class and declare the main method so that the program can be identified and start running.

Step 2:
In main method decalre two variables with appropriate data type declaration.

Step 3:
Perform the basic arithmatic operations (addition,subtraction,multiplication,division).

Step 4:
Print the output using "System.outprintln" to see the results.

Step 5:
The program completes it's execution and the output will be displayed eventually.

### PROGRAM:
```
import java.util.Scanner;
public class math_calc
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter first number: ");
        int a = sc.nextInt();
        System.out.print("Enter second number: ");
        int b = sc.nextInt();
        System.out.println("Addition = "+(a+b));
        System.out.println("Subtraction = "+(a-b));
        System.out.println("Multiply = "+(a*b));
        System.out.println("Divide = "+(a/b));
        System.out.println("Reminder = "+(a%b));
    }
}
```
### OUTPUT:
![image](https://github.com/Lakshmipriya-P-AI/Arithmetic-Operation/assets/93427923/b1136ba4-89d2-4171-b1af-4d0ab79b90c9)

### RESULT:
Thus a java program is written to print the sum, multiply, subtract, divide and remainder of two numbers.
