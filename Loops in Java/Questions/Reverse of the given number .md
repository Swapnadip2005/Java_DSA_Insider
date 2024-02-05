# Print Reverse of the given number
```java
import java.util.*;

public class Reverse {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);

        System.out.print("Enter a Number: ");
        int n = sc.nextInt(); // n = 98652
        int reverse = 0;

        while (n > 0) {
            int lastDigit = n % 10;
            reverse = reverse * 10 + lastDigit;
            n /= 10;
        }
        System.out.println(reverse); // Output = 25689
    }
}
```
