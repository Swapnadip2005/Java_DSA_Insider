# else - if Statement
The `else - if statement` is an extension of the `if - else statement`. It allows you to `test multiple conditions` and execute different blocks of code based on the `first condition` that evaluates to `true`.
# Syntax 
```java
if(condition 1)  {
  // condition 1 is true
}
else if(condition 2) {
  // condition 1 is false
}
else {
  // condition 1 & condition 2 both are false
}
```
# Example (Positive, Negative or Zero)
```java
int z = -6;

if(z > 0) {
    System.out.println(z + " is positive");
}
else if(z < 0) {
    System.out.println(z + " is negative"); // Output = -6 is negative
}
else {
    System.out.println(z + " is zero"); 
}
```
