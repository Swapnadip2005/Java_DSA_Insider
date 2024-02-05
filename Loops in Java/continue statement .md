# continue statement

In Java, the `continue statement` is used to `skip the rest of the code inside a loop for the current iteration and move on to the next iteration`. It is often used `when a specific condition is met`, and we want to skip the remaining code in the loop for that particular iteration.

# Example
- ### In for loop
```java
for (int i = 0; i < 5; i++) {
    if (i == 2) {
        System.out.println("Skipping iteration at i = 2");
        continue;
    }
    System.out.println("Iteration " + i);
}
```
#### Output
```arduino
Iteration 0
Iteration 1
Skipping iteration at i = 2
Iteration 3
Iteration 4
```
- ### In while loop
```java
int i = 0;
while (i < 5) {
    if (i == 2) {
        System.out.println("Skipping iteration at i = 2");
        i++;
        continue;
    }
    System.out.println("Iteration " + i);
    i++;
}
```
- ### In do - while loop
```java
int i = 0;
do {
    if (i == 2) {
        System.out.println("Skipping iteration at i = 2");
        i++;
        continue;
    }
    System.out.println("Iteration " + i);
    i++;
} while (i < 5);
```
