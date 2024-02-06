# Print the Pattern

![Pattern #2](https://github.com/Swapnadip2005/Java_DSA_Insider/assets/149895037/8a1d5c57-d2dd-4a5f-ae79-a8ced4c87f86)

```java
public class Pattern2 {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
          for (int j = 5; j >= i; j--) {
            System.out.print("*");
          }
          System.out.println();
        }
    }
}
