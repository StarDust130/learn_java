# Unit 2 README 🧱

## Most Important Q&A (Write In Exam) ⭐

### 1) Q: What is inheritance? Why used?

A: Inheritance means child class gets properties and methods of parent class.
It is used for code reuse and easy maintenance.

Example:

```java
class Animal {}
class Dog extends Animal {}
```

### 2) Q: Types of inheritance?

A:

- Single: one child from one parent.
- Multilevel: child of child.

Example:

```java
class A {}
class B extends A {}
class C extends B {}
```

### 3) Q: What is method overriding?

A: Child class gives new definition of parent method with same name and parameters.

Example:

```java
class Animal {
    void sound() { System.out.println("Animal sound"); }
}
class Dog extends Animal {
    void sound() { System.out.println("Bark"); }
}
```

### 4) Q: What is abstract class?

A: Abstract class cannot be instantiated. It may have abstract and normal methods.

### 5) Q: Use of final keyword in inheritance?

A:

- final class: cannot be inherited.
- final method: cannot be overridden.
- final variable: value cannot change.

### 6) Q: What is package?

A: Package is a group of related classes. It avoids name conflict and organizes code.

Example:

```java
package mypack;
import java.util.Scanner;
```

### 7) Q: What is interface?

A: Interface contains abstract methods. Class uses implements keyword.
Java supports multiple inheritance through interfaces.

Example:

```java
interface Printable {
    void print();
}
class Test implements Printable {
    public void print() { System.out.println("Print"); }
}
```

### 8) Q: Class vs interface?

A:

- Class can have complete methods and objects.
- Interface has method declarations and full abstraction idea.

## Last Revision ✅

- Inheritance types
- Overriding
- Abstract class
- Interface + implements
- final keyword uses
