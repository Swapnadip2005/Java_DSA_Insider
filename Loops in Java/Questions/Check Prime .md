# Check if a number is Prime or not
```java
import java.util.*;

public class Prime {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);

        System.out.print("Enter a no. to check Prime: ");
        int num = sc.nextInt();
        int flag = 0;

        for (int i = 1; i <= num; i++) {
            if(num % i == 0) {
                flag++;
            }
        }
        if(flag == 2) {
            System.out.println(num + " is a Prime Number");
        } else {
            System.out.println(num + " is not a Prime Number");
        }
    }
}
```
