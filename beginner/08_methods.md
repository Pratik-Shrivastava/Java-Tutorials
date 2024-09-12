# Functions and Methods in Java

In Java, methods (commonly referred to as functions in other languages) are blocks of code designed to perform specific tasks. Methods help in code reusability and organization, making the code more modular.

## Key Concepts

## 1. **Method Declaration**
A method must be declared within a class and define the following:
- **Return Type**: Specifies the type of value the method will return. If no value is returned, it uses `void`.
- **Method Name**: The name used to call the method.
- **Parameters**: A list of variables passed into the method, enclosed in parentheses.
- **Body**: The block of code that runs when the method is called, enclosed in curly braces `{}`.

## Example
```java
public class Calculator {

    // Method declaration
    public void add() {
        
    }
}
```

## 2. **Method Signature**
The method signature consists of the **method name** and **parameter list**. It is used to uniquely identify a method.

## Example
```java
public class Printer {
    
    public void printMessage(String message) {
        System.out.println(message);
    }
    
    public void displayMessage(String message) {
        System.out.println(message);
    }

    
}
```

## 3. **Return Statement**
The return statement is used to exit a method and optionally pass a value back to the caller. If the method’s return type is `void`, no value is returned.

## Example
```java
public class SquareCalculator {

    // Returns the square of a number
    public int square(int number) {

        return number * number;  // Return result
    }
}
```

### 4. **Method Overloading**
- Method overloading allows multiple methods with the **same name** but **different parameter lists** within the same class. 
- The method called depends on the **number** and **type** of arguments passed.

```java
public class Display {
    // Method overloading: same method name with different parameters

    // 1. Number of parameters is different

    public int sum(int num1, int num2) {
        return num1 + num2;
    }

    public int sum(int num1, int num2, int num3) {
        return num1 + num2 + num3;
    }

    // 2. Type of parameter is different.

    public void print(String name) {
        System.out.println("My name is " + name);
    }

    public void print(int roll) {
        System.out.println("My roll is " + roll);
    }

    
}
```

## 5. **Static vs Instance Methods**
- **Static Methods**: Belong to the class and can be called without creating an object. Declared with the `static` keyword.
- **Instance Methods**: Belong to objects and require an instance of the class to be called.

## Example
```java
public class MathOperations {
    // Static method
    public static int add(int a, int b) {
        return a + b;
    }

    // Instance method
    public int multiply(int a, int b) {
        return a * b;
    }
}
```

## 6. **Method Parameters**
Parameters allow methods to accept data. There are two types:
- **Pass by Value**: The actual value is passed, and changes made inside the method do not affect the original value.
- **Pass by Reference (Objects)**: The reference to the object is passed, and changes made inside the method can affect the object.

## Example

```java
public class Person {

    // Pass by value (for primitive types)

    public void changeValue(int age) {
        age = 30;  // Not affect the original variable
    }

    // Pass by reference (for objects)

    public void updateName(Person person) {
        person.name = "John";  // Affect the original object
    }
}
```


## 7. **Void Methods**
A method with a return type of `void` does not return any value. It is used for methods that perform an action but do not need to return information.

## Example
```java
public class Logger {
    // Void method performs an action without returning any value
    public void logMessage(String message) {
        System.out.println("Log: " + message);
    }
}
```

## 8. **Recursion**
A method can call itself to perform a recursive task. Recursion is often used to solve problems that can be broken down into smaller subproblems.

## Example
```java
public class FactorialCalculator {
    // Recursive method to calculate factorial
    
    public int factorial(int n) {
        if (n == 1) {
            return 1;  // Base case
        }
        return n * factorial(n - 1);  // Recursive call
    }
}
```


---

Methods are fundamental building blocks in Java programming, promoting reusable, organized, and maintainable code.
