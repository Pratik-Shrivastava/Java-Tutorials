# Java Operators

In Java, operators are special symbols used to perform operations on variables and values. They are classified based on their function.

## 1. Arithmetic Operators
Arithmetic operators are used to perform mathematical operations such as addition, subtraction, multiplication, etc.

| Operator | Description           |
|----------|-----------------------|
| `+`      | Addition              |
| `-`      | Subtraction           |
| `*`      | Multiplication        |
| `/`      | Division              |
| `%`      | Modulus (remainder)   |


## Examples

```java
int a = 10;
int b = 3;

int sum = a + b;        // sum is 13
int difference = a - b; // difference is 7
int product = a * b;    // product is 30
int quotient = a / b;   // quotient is 3
int remainder = a % b;  // remainder is 1
```

These operators are mainly used for calculations on numeric data types.

---

## 2. Assignment Operators
Assignment operators are used to assign values to variables.

| Operator | Description                     |
|----------|---------------------------------|
| `=`      | Assigns right operand to left   |
| `+=`     | Adds right operand to left and assigns the result to the left operand |
| `-=`     | Subtracts right operand from left and assigns the result to the left operand |
| `*=`     | Multiplies right operand with left and assigns the result to the left operand |
| `/=`     | Divides left operand by right and assigns the result to the left operand |
| `%=`     | Modulus of left operand by right and assigns the result to the left operand |

## Examples

```java
int a = 10;

a += 5;  // a becomes 15
a -= 3;  // a becomes 12
a *= 2;  // a becomes 24
a /= 4;  // a becomes 6
a %= 5;  // a becomes 1
```
Assignment operators simplify operations where a value is modified and then reassigned to the same variable.

---

## 3. Relational (Comparison) Operators
Relational operators are used to compare two values. The result of a comparison is always a boolean (`true` or `false`).

| Operator | Description           |
|----------|-----------------------|
| `==`     | Equal to              |
| `!=`     | Not equal to          |
| `>`      | Greater than          |
| `<`      | Less than             |
| `>=`     | Greater than or equal |
| `<=`     | Less than or equal    |

## Examples
```java
int a = 10;
int b = 20;

boolean isEqual = (a == b);         // false
boolean isNotEqual = (a != b);      // true
boolean isGreaterThan = (a > b);    // false
boolean isLessThan = (a < b);       // true
boolean isGreaterOrEqual = (a >= b);// false
boolean isLessOrEqual = (a <= b);   // true
```

These operators are commonly used in conditional statements.

---

## 4. Logical Operators
Logical operators are used to combine multiple boolean expressions.

| Operator | Description                                |
|----------|--------------------------------------------|
| `&&`     | Logical AND (returns true if both conditions are true) |
| `ll`     | Logical OR (returns true if at least one condition is true) |
| `!`      | Logical NOT (reverses the boolean value of a condition) |

## Examples
```java
boolean x = true;
boolean y = false;

boolean andResult = x && y;     // false
boolean orResult = x || y;      // true
boolean notResult = !x;         // false
```

They are primarily used in control flow statements like `if-else` conditions.

---

## 5. Unary Operators
Unary operators require only one operand and are used to perform operations such as incrementing, decrementing, or negating a value.

| Operator | Description                 |
|----------|-----------------------------|
| `+`      | Unary plus (positive)       |
| `-`      | Unary minus (negation)      |
| `++`     | Increment (increases value by 1)  |
| `--`     | Decrement (decreases value by 1)  |
| `!`      | Logical NOT                 |

## Examples
```java
int a = 5;

int b = a++;    // b becomes 5 
                // a becomes 6 (post-increment) 
int c = ++a;    // c becomes 7
                // a becomes 7 (pre-increment)

a--;  // a becomes 6 (post-decrement)
--a;  // a becomes 5 (pre-decrement)

int negation = -a;  // negation is -5

boolean flag = true;
flag = !flag;       // flag becomes false
```
Unary operators are useful in loops and conditions.


---

## 6. Bitwise Operators
Bitwise operators operate on bits of integer types and perform bit-level operations.

| Operator | Description         |
|----------|---------------------|
| `&`      | Bitwise AND          |
| `l`      | Bitwise OR           |
| `^`      | Bitwise XOR          |
| `~`      | Bitwise NOT          |
| `<<`     | Left shift           |
| `>>`     | Right shift          |

These operators are typically used in low-level programming, often involving flags or bit manipulation.

## Examples
```java
int a = 5;  // 0101 in binary
int b = 3;  // 0011 in binary

int andResult = a & b;  // 0001 (1 in decimal)
int orResult = a | b;   // 0111 (7 in decimal)
int xorResult = a ^ b;  // 0110 (6 in decimal)
int notResult = ~a;     // 1010 (two's complement of -6)

int leftShift = a << 1;  // 1010 (10 in decimal)
int rightShift = a >> 1; // 0010 (2 in decimal)
```

---

## 7. Ternary Operator
The ternary operator is a shorthand for an `if-else` statement. It takes three operands and is used to evaluate a condition and return one of two values based on the result.

| Operator | Description                     |
|----------|---------------------------------|
| `?:`     | Ternary (condition ? true : false) |

## Example
```java
int a = 10;
int b = 20;

int max = (a > b) ? a : b;  // max will be 20
```

It simplifies conditional expressions by condensing them into a single line of code.

---

## 8. Instanceof Operator
The `instanceof` operator is used to test whether an object is an instance of a specific class or subclass.

| Operator    | Description                      |
|-------------|----------------------------------|
| `instanceof`| Checks if an object is an instance of a specific class or interface |

```java
String str = "Hello";
boolean result = str instanceof String;  // true
```

This is useful for type checking before performing certain operations on an object.

---

