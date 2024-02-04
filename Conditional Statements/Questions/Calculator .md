# Calculator (Sum, Subtract, Multiply and Divison)
```java
import java.util.*;

public class JavaBasics {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);

        System.out.print("Enter 1st Number: ");
        int a = sc.nextInt();
        System.out.print("Enter 2nd Number: ");
        int b = sc.nextInt();

        System.out.print("Enter Operator: ");
        char operator = sc.next().charAt(0);

        switch (operator) {
            case '+':
                System.out.println(a+b);
                break;
            case '-':
                System.out.println(a-b);
                break;
            case '*':
                System.out.println(a*b);
                break;
            case '/':
                System.out.println(a/b);
                break;
            default:
                System.out.println("Invalid Operator");
        }
    }
}
```
