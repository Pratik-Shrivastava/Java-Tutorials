# Variables and Data Types in Java

In Java, variables are used to store data that can be manipulated within a program. Each variable in Java must be declared with a specific data type, which determines what kind of data it can hold, such as integers, floating-point numbers, or characters.

## Variables in Java

A **variable** is a container for storing data values. Each variable must have a data type, which defines the type of data it can hold.

### Variable Declaration

To declare a variable in Java, you specify the data type followed by the variable name.

```java
dataType variableName;
```

## Example

```java
int roll = 45;
```

## Types of Variables in Java

Java has three types of variables:

1. **Local Variables**: Declared inside methods, constructors, or blocks. They are only accessible within the method or block in which they are declared.
   
2. **Instance Variables**: Declared inside a class but outside methods. They are associated with objects and are accessible by all methods of the class.

3. **Static Variables**: Declared inside a class with the `static` keyword. They are shared among all objects of the class.

## Data Types in Java

Java is a **statically-typed** language, meaning each variable must have a specified data type at the time of declaration. There are two categories of data types in Java:

### 1. **Primitive Data Types**

These are the most basic data types in Java. Java provides 8 primitive data types:

- `byte`: 8-bit integer, range: -128 to 127
- `short`: 16-bit integer, range: -32,768 to 32,767
- `int`: 32-bit integer, range: -2^31 to 2^31 - 1
- `long`: 64-bit integer, range: -2^63 to 2^63 - 1
- `float`: 32-bit floating-point, used for single precision decimal numbers
- `double`: 64-bit floating-point, used for double precision decimal numbers
- `char`: 16-bit Unicode character
- `boolean`: Represents two values: `true` or `false`

### Example of Primitive Data Type

```java
byte b = 10; 
int number = 100; 
long aadharNumber = 457845784545;
float cost = 78.02F; // <--important
double price = 99.99; 
char grade = 'A'; 
boolean isJavaFun = true;
```

### 2. **Reference Data Types**

Reference data types refer to objects and are declared using constructors of classes. They include strings, arrays, and objects of custom classes.
### Example of Reference Data Type

```java
String name = "Pratik";
int[] numbers = {1, 2, 3, 4, 5};
```

## Type Casting

In Java, you can convert a variable from one data type to another, which is known as **type casting**. There are two types of casting:

1. **Implicit Casting** (automatically) – converting a smaller type to a larger type size.
    - `byte -> short -> int -> long -> float -> double`

```java
long num = 7845; 
float floatNum = num; 
```


   
2. **Explicit Casting** (manually) – converting a larger type to a smaller type size.
    - `double -> float -> long -> int -> short -> byte`

```java
double price = 99.99;
int intPrice = (int) price;
```

## Revision Notes
- ### Implicit Typecasting : long -> float


