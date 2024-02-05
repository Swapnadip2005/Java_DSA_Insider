# What is wrong in the following program ?
```java
public class Solution {
  public static void main(String args[]) {
    for(int i = 0; i <= 5; i++ ) {
      System.out.println("i = " + i );
    }
    System.out.println("i after the loop = " + i );
  }
}
```
# Answer
`Scope of variable` is referred to the part of the program where the variable can be used.
In this program `variable i is declared in the for loop`. So `scope of variable i is limited to the for
loop only` i.e. between { and } of the for loop. There is a print statement after the for loop
where `variable i is used which means i is used out of scope`. This leads to `compilation errors`.
The program given `will not run` and `give an error` instead. To correct the program, the `variable i
needs to be declared outside the for loop`.

# Correct Code
```java
public class Solution {
  public static void main(String args[]) {
    int i;  // Declare i outside the loop to extend its scope
    for(i = 0; i <= 5; i++ ) {
      System.out.println("i = " + i );
    }
    System.out.println("i after the loop = " + i );
  }
}
```
