# Functions or Methods

In Java, a `Function` or `Methods` is a block of code that performs a specific task. They are designed to  
`break down a program into smaller and manageable pieces, making the code easier to understand, debug, and maintain`.

# Syntax

- ### Without Parameters
  ```java
  returnType name() {
    //Body
    return Statement;
  }
  ```
  ### Example
  ```java
  public class Function {
    public static int Add() {

        int sum, a=5, b=10;
        sum = a+b;
        return sum;
    }
    public static void main(String[] args) {
        System.out.println("The sum is: " + Add());
    }
  }
  ```

- ### With Parameters
  ```java
  returnType name(type parameter1, type parameter2) {
    //Body
    return Statement;
  }
  ```
  ### Example
  ```java
  public class Function {
    public static int Add(int a, int b) {
        return a + b;
    }
    public static void main(String[] args) {
        int sum = Add(10, 5);
        System.out.println("The sum is: " + sum);
    }
  }
  ```
