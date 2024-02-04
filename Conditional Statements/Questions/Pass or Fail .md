# Check if a student will PASS or FAIL using Ternary Operator
| Marks | Result |
|-------|--------|
| > = 33 | PASS |
| < 33 | FAIL |

```java
import java.util.*;

public class Student {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);

        System.out.print("Enter Marks: ");
        int marks = sc.nextInt();

        String result = (marks > = 33) ? "PASS" : "FAIL";
        System.out.println(result);
    }
}
```
