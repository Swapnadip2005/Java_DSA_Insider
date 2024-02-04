# Income Tax Calculator

| Income | Tax |
|--------|-----|
| Less than 5 Lakhs | 0% tax |
| Between 5 - 10 Lakhs | 20% tax |
| More than 10 Lakhs | 30% tax |

```java
import java.util.*;

public class IncomeTax {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);

        int income = sc.nextInt();
        int tax;

        if (income < 500000) {
            tax = 0;
        }
        else if(income >= 500000 && income <= 1000000) {
            tax = (int) (income * 0.2);
        }
        else {
            tax = (int) (income * 0.3);
        }
        System.out.println("Your Income tax is: "  + tax);
    }
}
```
