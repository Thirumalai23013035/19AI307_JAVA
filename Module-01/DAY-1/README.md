# Ex.No:1(A) CLASS & OBJECTS

## AIM:
To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :
1.	Start the program.
2.	Define a class named 'Student'
3.	Declare a String variable 'name' and initialize it with the value "John"
4.	Declare a String variable 'address' and initialize it with the value "Chennai"
5.	Define a class named 'Test'
6.	Define the 'main' method within the 'Test' class
7.	Create an object 'obj' of the 'Student' class
8.	Print the value of 'name' and 'address' variables of the 'obj' object
9.	End



## PROGRAM:
 ```

```

## Sourcecode.java:
```
public class Student
{
    String name,address;
    int rollno;
}
public class Main {
    public static void main(String[] args) {
        Student obj= new Student();   
        obj.name="John";
        obj.address="Chennai";
        obj.rollno=10;
        System.out.println(obj.name+" "+obj.address+" "+obj.rollno);
    }   
}
```
## OUTPUT:

<img width="735" height="215" alt="Screenshot 2025-10-09 202643" src="https://github.com/user-attachments/assets/36550103-59e0-4041-81bc-a4b750a3b7b2" />


## RESULT:

Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.

