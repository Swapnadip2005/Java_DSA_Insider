# Switch Statement
In Java, `The Switch Statement` is used for decision-making when you have `multiple possible execution paths` based on the value of an expression. It's an `alternative to a series of if-else statements` when you need to compare a `single variable against multiple possible values`.
# Syntax
```java
switch (expression) {
    case value1:
        // code to be executed if expression equals value1
        break;
    case value2:
        // code to be executed if expression equals value2
        break;
    // additional cases as needed
    default:
        // code to be executed if none of the cases match
}
```
# Example
```java
int dayOfWeek = sc.nextInt();

switch (dayOfWeek) {
    case 1:
        System.out.println("The day is Sunday");
        break;
    case 2:
        System.out.println("The day is Monday");
        break;
    case 3:
        System.out.println("The day is Tuesday");
        break;
    case 4:
        System.out.println("The day is Wednesday");
        break;
    case 5:
        System.out.println("The day is Thrusday");
        break;
    case 6:
        System.out.println("The day is Friday");
        break;
    case 7:
        System.out.println("The day is Saturday");
        break;
    default:
        System.out.println("Invalid Day Number");
}
```
