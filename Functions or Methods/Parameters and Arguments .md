# Parameters
`Parameters are variables declared in the Function`, and they act as placeholders for values that are passed to the function when it's called. They define the `type and order of the values the function expects to receive`.
# Arguments
`Arguments are the actual values that are passed to a function when it is called`. These values are supplied in the function call and correspond to the parameters defined in the `Function`.

```java
import java.util.*;
public class Function {
  public static int Add(int num1, int num2) {
      return num1 + num2;
  }
  public static void main(String[] args) {
      Scanner sc = new Scanner(System.in);
      int a = sc.nextInt();
      int b = sc.nextInt();
      System.out.println("The sum is: " + Add(a,b));
  }
}
```
#### Here, `int num1 and int num2` are referred as `Parameters or Formal Parameters` and in `Add(a,b)`, `a and b` referred as `Arguments or Actual parameters`.
