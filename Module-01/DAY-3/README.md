# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End


## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: THIRUMALAI V
RegisterNumber: 212223040229
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Demo{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        if(n==0)
        {
            System.out.println("Given number is Zero");
        }
        else
        {
            System.out.println(n+" is Non-Zero");
        }
    }
}
```
## OUTPUT:

<img width="711" height="280" alt="Screenshot 2025-10-09 203423" src="https://github.com/user-attachments/assets/a1fa5544-43b5-493c-87dc-ec01dcc79c5d" />


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.


