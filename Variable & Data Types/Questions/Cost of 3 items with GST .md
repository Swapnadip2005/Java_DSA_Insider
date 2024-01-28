# Enter the cost of 3 items from the user (using float) - a pencil, a pen and an eraser. Print the Total cost of the items as their bill. Also add 18% GST Tax to the items in the bill.

```java
import java.util.*;

public class Bill {
    public static void main(String[] args) {
        Scanner sc = new Scanner (System.in);
        float pencil = sc.nextFloat();
        float pen = sc.nextFloat();
        float eraser = sc.nextFloat();
        float total = pencil + pen + eraser ;
        System.out.println("Total Bill: " + total);

        float new_total = total + (0.18f * total);
        System.out.println("Total Bill with 18% GST: " + new_total);
    }
}
```
