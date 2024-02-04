# Ternary Operator
In Java, `The Ternary Operator` is a shorthand way of writing an `if-else statement`. It is also known as the `Conditional Operator`.
# Syntax
### result = (condition) ? Statement 1 : Statement 2 ;
Here, `condition` is evaluated first. If it is `true`, `Statement 1` is executed, and its `result is assigned` to the `variable result`. If the condition is `false`, `Statement 2` is executed, and its `result is assigned` to `variable result`.
# Examples
```java
int x = 10;
int y = 20;

int max = (x > y) ? x : y;
System.out.println("The maximum is: " + max); // Output = The maximum is: 20
```
```java
int x = 10;

String type = (x % 2 == 0) ? "Even" : "Odd";
System.out.println(type); // Output = Even
```
