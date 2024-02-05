# Print numbers from 1 to n
```java
import java.util.*;

public class JavaBasics {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);

        System.out.print("Enter the value of n: ");
        int n = sc.nextInt();
        int i = 1;
        while(i <= n) {
            System.out.print(i + " ");
            i++;
        }
    }
}
```
