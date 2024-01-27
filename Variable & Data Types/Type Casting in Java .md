# Type Casting (Narrowing or Explicit Conversion)

```java
float num = 99.999f;
int n = (int) num;
System.out.println(n);
```
#### Output - 99

> [!NOTE]  
> 99.999f because java by default take decimal values as double, so to convert it into float we use 'f'

```java
char ch = 'a';
int num = ch;
System.out.println(num);
```
#### Output - 97

> [!NOTE]
> When we convert char to int we get the ASCII value of that char as output in Java.

> [!IMPORTANT]  
> In Java, we can work with `ASCII (American Standard Code for Information Interchange)` values using `char` and `int` data types. Each character in Java corresponds to a specific ASCII value.
