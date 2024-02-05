# break statement

In Java, the `break statement` is used to `terminate the execution of a loop or switch statement` prematurely. It is often used when a certain condition is met, and you want to `exit the loop or switch statement immediately`. The break statement can be used with `for, while, do-while loops, and switch statements`.

# Example
- ### In for loop
```java
for (int i = 0; i < 10; i++) {
    if (i == 5) {
        System.out.println("Breaking the loop at i = 5");
        break;
    }
    System.out.println("Iteration " + i);
}
```
#### Output
```arduino
Iteration 0
Iteration 1
Iteration 2
Iteration 3
Iteration 4
Breaking the loop at i = 5
```
- ### In while loop
```java
int i = 0;
while (i < 10) {
    if (i == 5) {
        System.out.println("Breaking the loop at i = 5");
        break;
    }
    System.out.println("Iteration " + i);
    i++;
}
```
- ### In do - while loop
```java
int i = 0;
do {
    if (i == 5) {
        System.out.println("Breaking the loop at i = 5");
        break;
    }
    System.out.println("Iteration " + i);
    i++;
} while (i < 10);
```
