# Inputs in Java

- next( )
- nextLine( )
- nextInt( )
- nextByte( )
- nextFLoat( )
- nextDouble( )
- nextBoolean( )
- nextShort( )
- nextLong( )

> [!NOTE]  
> `next()` returns the first word as output.

# How to take User input in Java ?

We can take User input in Java using :
- `BufferedReader Class`
- `Scanner Class`

# Example using `Scanner Class`

For using `Scanner Class` we have to import a package name `java.util`

```java
import java.util.*;

public class Basics {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String s = sc.next();
        System.out.println(s);
    }
}
```
Input - `Hello World`  
Output - `Hello`
