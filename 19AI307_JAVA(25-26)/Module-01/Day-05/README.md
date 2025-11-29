# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to calculate the power of a given number.

## AIM:
To write a Java program to compute the power of a number using the Math.pow() function in Java.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the base value from the user.
4. Read the exponent value from the user.
5. Use the Math.pow(base, exponent) function to calculate the power.
6. Display the result.
7. Stop the program.


## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Vasanthi Sivasankar
RegisterNumber:  212223040234
*/
```

## SOURCE CODE:
```
import java.util.*;

public class prog {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        double base = sc.nextDouble();
        double exponent = sc.nextDouble();
        double result = Math.pow(base, exponent);

        System.out.println(base + " raised to the power of " + exponent + " is: " + result);
    }
}
```

## OUTPUT:
<img width="1232" height="416" alt="day5" src="https://github.com/user-attachments/assets/9abb9e7c-b722-4724-ad18-00c04b225ab0" />

## RESULT:
Thus, the Java program to calculate the power of a given number using Math function was successfully executed.
