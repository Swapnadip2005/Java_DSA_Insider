# Print the Total sum of first n natural numbers

```java
import java.util.*;

public class JavaBasics {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);

        System.out.print("Enter the value of n: ");
        int n = sc.nextInt();
        int i = 1;
        int sum = 0;
        while(i <= n) {
            sum += i;
            i++;
        }
        System.out.println("Total Sum: " + sum);
    }
}
```
