# Exp6_Create-a-method-to-calculate-power-of-a-number-raised-to-other
## AIM:
### Create a program to calculate the power of a number raised to other number respectively.
## PROCEDURE:
### 1.Create the class and declare the main method so that the JVM will identify the main program to run.
### 2.Declare two variables and accept the input from user.
### 3.Inside for loop declare an if condition to check whether the given number is even or not.
### 4.To accept the inputs from user import Scanner and get the input and store them.
### 5.Use MATH library to use pow() function and assign the values to calculate their power.
### 6.The program will be executed after the compilation and print the results.
## PROGRAM:
```
// NAME :PAVITHRA G
// ROLLNO: 212221240036
import java.util.Scanner;
public class power {
    public static void main(String[] args) {
        int a,b;
        double result;
        Scanner sc=new Scanner(System.in);
        a=sc.nextInt();
        b=sc.nextInt();
        result =Math.pow(a,b);
        System.out.println("Power for given number: "+result);

    }
}

```
## RESULT:
![image](https://github.com/gpavithra673/Exp6_Create-a-method-to-calculate-power-of-a-number-raised-to-other/assets/93427264/395dfe61-17bf-4db5-b7ed-33438788691a)
