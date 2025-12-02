Skip to content
Navigation Menu
Platform
Solutions
Resources
Open Source
Enterprise
Pricing

Search or jump to...
Sign in
Sign up
vasundrasriravi
/
19AI307_JAVA
Public
forked from Priyasenthil17/19AI307_JAVA
Code
Pull requests
Actions
Projects
Security
Insights
Files
Go to file
Module-01
Module-02
DAY-1
README.md
DAY-2
README.MD
DAY-3
README.md
DAY-4
README.md
DAY-5
Module-03
Module-04
Module-05
Module-06
Module-07
Module-08
Module-09
Module-10
Module-11
Module-12
README.md
19AI307_JAVA/Module-02/DAY-4
/README.md
vasundrasriravi
vasundrasriravi
Update README.md
c7a6d38
 · 
last month
19AI307_JAVA/Module-02/DAY-4
/README.md

Preview

Code

Blame
66 lines (54 loc) · 1.58 KB
# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY
## PROGRAM:
# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that returns the sum of all the values in a 2D array.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: THIRUMALAI V
RegisterNumber: 212223040229
*/
```

## Sourcecode.java:
```
public class Main
{
    public static void sum(int[][] arr)
    {
        int sum = 0;
        for(int i = 0; i < arr.length; i++)
        {
            for(int j = 0; j < arr[0].length; j++)
            {
                sum = sum + arr[i][j];
            }
        }
        System.out.print("Sum of all elements is: " + sum);
    }
    public static void main(String[] args)
    {
        int[][] arr = {
                {1, 2, 3, 4, 5},
                {2, 4, 6, 8, 10},
                {1, 3, 5, 7, 9}
        };
        sum(arr);
    }
}
```
## OUTPUT:

<img width="961" height="213" alt="Screenshot 2025-10-09 205104" src="https://github.com/user-attachments/assets/7aee0f7d-d7be-415f-9708-1c6f52ce5bef" />


## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.



19AI307_JAVA/Module-02/DAY-4/README.md at main · vasundrasriravi/19AI307_JAVA · GitHub

