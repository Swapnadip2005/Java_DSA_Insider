# Write a Java program that takes a year from the user and print whether that year is a Leap Year or not
```java
import java.util.*;

public class LeapYear {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);

        System.out.print("Enter a Year: ");
        int year = sc.nextInt();

        if (year%100 == 0 && year%400 == 0 || year%100 != 0 && year%4 == 0) {
            System.out.println(year + " is a Leap Year");
        }
        else {
            System.out.println(year + " is not a Leap Year");
        }
    }
}
```
