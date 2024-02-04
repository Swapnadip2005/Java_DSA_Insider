# Nested if Statements
We can also `nest if statements inside each` other to create more `complex decision-making structures`.

# Syntax
```java
if(condition) {
  if (condition 1) {
    // condition & condition 1 are true
  }
  else {
    // condition 1 is false
  }
}
else {
  // condition is false
}
```
# Example (Positive or Negative)
```java
int a = 5;
int b = -10;

if (a > 0) {
    if (b > 0) {
        System.out.println("Both" + a + "and" + b + "are positive");
    } else {
        System.out.println(a + "is positive, but" + b + "is not"); // Output = 5 is positive, but -10 is not
    }
} else {
    System.out.println(a + "is not positive");
}
```
