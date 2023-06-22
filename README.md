# Ex-03 Java program to print the even numbers from a range
## Aim:-
To write a java program to print the even numbers between 1-20

## Procedure:-
### Step 1:
Import the required packages

### Step 2:
Get the start and end value for the even numbers to be printed.

### Step 3:
Display the even numbers using loop.

### Step 4:
Stop the execution.

### Program:-
#### Developed By : Sarankumar J
#### Register Number : 212221230087
```java
import java.util.*;
public class EvenNumbers {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter start and stop value: ");
        int start=sc.nextInt();
        int end=sc.nextInt();
        System.out.print("Even numbers between "+start+" and "+end+" is ");
        for(int i=start+2;i<end;i+=2)
        {
            System.out.print(i+" ");
        }

    }
}
```
## Output:-
![image](https://github.com/SarankumarJ/Java-Ex-04/assets/94778101/abdf1b75-fb10-4a0f-bd30-8a5715e8d734)

## Result:-
A java program to print the even numbers between 1-20 has been executed successfully.
