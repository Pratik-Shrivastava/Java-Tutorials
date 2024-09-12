# Object-Oriented Programming (OOP) Basics in Java

Object-Oriented Programming (OOP) is a paradigm in Java that revolves around the concept of "objects," which can contain both data and methods. OOP promotes better code organization, reusability, and scalability.

---

## 1. **Class**
A class is a blueprint or template for creating objects. It defines the properties (fields) and behaviors (methods) that the objects created from it will have.

---

## 2. **Object**
An object is an instance of a class. It represents a specific entity in memory that has attributes (data) and behaviors (methods) defined by the class.

---

## 3. **Encapsulation**
Encapsulation is the concept of bundling data (fields) and methods that operate on the data into a single unit (class) and restricting access to the inner workings of that class. This is typically achieved using access modifiers like `private` and providing public getter and setter methods for controlled access.

---

## 4. **Inheritance**
Inheritance allows a new class to inherit the properties and methods of an existing class. This promotes code reusability. The class that is inherited from is called the **parent class** (or **superclass**), and the class that inherits is called the **child class** (or **subclass**).

---

## 5. **Polymorphism**
Polymorphism allows one method or object to take multiple forms. It can be achieved in two ways:
- **Method Overloading** (compile-time polymorphism): Same method name with different parameters.
- **Method Overriding** (runtime polymorphism): A subclass provides a specific implementation of a method already defined in its superclass.

---

## 6. **Abstraction**
Abstraction involves hiding the implementation details and exposing only the essential features of an object. This is often achieved through abstract classes and interfaces, which define abstract methods that must be implemented by subclasses.

---

## 7. **Constructor**
A constructor is a special method in a class that is called when an object is created. It is used to initialize the object's fields. Constructors can be overloaded to allow different ways of object initialization.

---

## 8. **Access Modifiers**
Java provides four access modifiers to control the visibility of fields, methods, and constructors:
- **Public**: Accessible from anywhere.
- **Private**: Accessible only within the same class.
- **Protected**: Accessible within the same package and subclasses.
- **Default** (no modifier): Accessible only within the same package.

---

## 9. **Interfaces**
An interface is a reference type in Java that contains only abstract methods (until Java 8, which introduced default and static methods). It is used to achieve abstraction and multiple inheritance, as a class can implement multiple interfaces.

---

## 10. **Packages**
Packages in Java are used to group related classes and interfaces into namespaces. They help organize code, avoid name conflicts, and provide access control.

---

These are the foundational concepts of Object-Oriented Programming in Java, providing structure and efficiency to code.
