# Loops
## 1. For Loop

A `for` loop is used to execute a block of code repeatedly for a specified number of times. The `for` loop has three main components:

- Initialization: Sets the starting point of the loop.
- Condition: Determines if the loop should continue or terminate.
- Increment/Decrement: Updates the loop counter after each iteration.

### It is ideal when the number of iterations is known beforehand.

## Example

```java
for (int i = 0; i < 5; i++) {

    System.out.println("Iteration: " + i);
}
```

---

## 2. While Loop

The `while` loop repeatedly executes a block of code as long as a specified condition remains true. The condition is checked before each iteration, and the loop continues until the condition becomes false.

### This loop is typically used when the number of iterations is not known beforehand.

## Example
```java
int i = 0;

while (i < 5) {

    System.out.println("Iteration: " + i);
    i++;
}
```

---

## 3. Do-While Loop

The `do-while` loop is similar to the `while` loop, but with one major difference: the code block is executed **at least once**, regardless of the condition. This is because the condition is checked **after** the loop body is executed. 

### It ensures that the block of code inside the loop runs at least once, even if the condition is false from the beginning.
## Example

```java
int count = 10;

do {

    System.out.println("Count is: " + count);
    count++;

} while (count < 5);        // condition is false
```

---

## 6. Break Statement

The `break` statement is used to terminate the loop or switch statement prematurely. When encountered, the program exits the current loop or `switch` block, and the execution continues from the next statement following the loop or `switch`.
## Example

```java
for (int i = 0; i < 10; i++) {

    if (i == 5) {
        break;  // Exit the loop when i is 5
    }
    System.out.println("i: " + i);
}
```

This is useful for stopping a loop when a certain condition is met, or when a case in a `switch` statement has been executed and no further checking is required.

---

## 7. Continue Statement

The `continue` statement is used to skip the current iteration of a loop and continue with the next one. When encountered, the remaining code inside the loop for the current iteration is ignored, and the next iteration begins immediately.

```java
for (int i = 0; i < 5; i++) {
    if (i == 2) {
        continue;  // Skip the rest of the loop when i is 2
    }
    System.out.println("i: " + i);
}
```

This is useful when you want to skip over some part of the loop based on a condition but continue looping.

---

