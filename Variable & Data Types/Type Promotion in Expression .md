# Type Promotion in Expression

- Java automatically promotes each `byte`, `short` or `char` operand to int when evaluating an expression.

![Untitled Diagram (1)](https://github.com/Swapnadip2005/Java_DSA_Insider/assets/149895037/5a63a275-ab18-45b1-a93f-6b0488925d41)

> [!NOTE]  
> All the value will be converted to `int` and the output will come as `int`

```java
int a = 25638;
byte b = 25 ;
char c = 'a';
System.out.println(a + b * c);
```
#### Output - 28063

- If one operand is `long`, `float` or `double` then the whole expression will be promoted to `long`, `float` or `double` respectively.

> [!NOTE]
> Output will be given in the **largest data type available in the expression**.

![Untitled Diagram](https://github.com/Swapnadip2005/Java_DSA_Insider/assets/149895037/455df096-a629-4b73-a1e8-df90d5fb30ab)

```java
int a = 25;
float b = 30.5f;
char c = 'a';
long d = 999999999;
System.out.println(a + b * c / d);
```
#### Output - 25.000004
