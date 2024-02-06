# Nested for loop 
In Java, we can use `nested for loops` to create a `loop inside another loop`. This allows you `to create more complex patterns or iterate over two-dimensional arrays`.

# Syntax
```java
for (initialization1; condition1; update1) {
    // code before the nested loop
    
    for (initialization2; condition2; update2) {
        // code to be executed
    }
    
    // code after the nested loop
}
```
# Example
```java
public class JavaBasics {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            for (int j = 1; j <= 5; j++) {
                System.out.print(i * j + "\t");
            }
            System.out.println();
        }
    }
}
```
# Output
```arduino
1	2	3	4	5	
2	4	6	8	10	
3	6	9	12	15	
4	8	12	16	20	
5	10	15	20	25	
```
