# Java Control Flow Statements

- Control flow statements determine the order in which instructions are executed in a Java program. 
- They control how the code flows based on conditions, loops, or choices. 
- Here is a breakdown of the major control flow statements in Java.

---

## 1. If-Else Statement

The `if-else` statement is used to perform conditional execution. Based on a condition, the program can execute a block of code if the condition is `true`, or an alternative block of code if it is `false`.

- **If**: Executes a block of code if a specified condition is true.
- **Else**: Executes an alternative block of code if the condition is false.
- **Else If**: Allows checking multiple conditions in sequence, and executes the corresponding block of code for the first true condition.

# If-Else Statement

```java
int num = 10;

if (num > 0) {
    System.out.println("Positive number");

} else if (num == 0) {
    System.out.println("Zero");

} else {
    System.out.println("Negative number");
}

```

This is typically used for decision-making in code.

---

## 2. Switch Statement

The `switch` statement is used for executing one block of code from multiple alternatives based on the value of an expression. Instead of using multiple `if-else` statements, `switch` makes the code more readable when checking a variable for a series of possible values.

```java
int day = 3;

switch (day) {

    case 1:
        System.out.println("Monday");
        break;

    case 2:
        System.out.println("Tuesday");
        break;

    case 3:
        System.out.println("Wednesday");
        break;

    default:
        System.out.println("Invalid day");
}
```

Each possible value is defined as a "case" in the `switch` block, and if a match is found, the corresponding code is executed. If no case matches, the `default` block is executed (if defined).

---


