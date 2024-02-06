# Print the Pattern

![Pattern #4](https://github.com/Swapnadip2005/Java_DSA_Insider/assets/149895037/a696e2cc-c659-4e53-9409-a54dabd67dc6)

```java
public class Pattern4 {
    public static void main(String[] args) {
        int letter = 65;
        for (int i = 1; i <= 4; i++) {
            for (int j = 1; j <= i ; j++) {
                System.out.print((char)(letter));
                letter++;
            }
            System.out.println();
        }
    }
}
```
