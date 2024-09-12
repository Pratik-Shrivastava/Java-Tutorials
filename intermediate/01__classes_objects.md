# Classes and Objects in Java

In Java, **Classes** and **Objects** are the fundamental building blocks of Object-Oriented Programming (OOP). They allow us to model real-world entities, organize code efficiently, and facilitate reuse.

## What is a Class?

A **class** is a blueprint for creating objects. It defines the properties (attributes) and behaviors (methods) that objects created from the class will have.

### Syntax of a Class

```java
class Student {
    
    String name;
    int roll;    
}
```
In the above example:

- The class `Studet` defines two attributes: `name`, and `roll`.


## What is an Object?

- An **object** is is an instance of a class. 
- Once a class is defined, we can create objects from it.
- Each object has its own values for the attributes defined in the class.

### Syntax of an Object

```java
class Student {
    
    String name;
    int roll;    
}

public class Main {
    public static void main(String[] args) {

        Student student1 = new Student();

        System.out.println("Student1 name = " + student1.name);
        System.out.println("Student1 roll = " + student1.roll);        

    }
}
```
## Creation of an Object

The object is created in three steps:
- ### Decalaration: Student student1
- ### Instantiation: new
- ### Initialization: Student()

## Constructors in Java

- A **constructor** is a special method used to initialize objects.
- It is called when an object of the class is created.
- If you don't define a constructor, Java provides a default constructor.

### Example of Constructor

```java
class Student {
    String name;
    int roll;

    Student(String name, int roll) {
        this.name = name;
        this.roll = roll;
    }

    void introduce() {
        System.out.println("Hi, I'm " + name + " and my roll number is " + roll + ".");
    }
}
```






