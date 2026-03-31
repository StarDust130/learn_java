# Unit 1 README 🚀

## Most Important Q&A (Write In Exam) ⭐

### 1) Q: What is Java? Write 4 features.

A: Java is a high-level, object-oriented programming language used for software, web, and apps.
Features: platform independent, secure, robust, object oriented.

Example:

```java
class Hello {
    public static void main(String[] args) {
        System.out.println("Hello Java");
    }
}
```

### 2) Q: What is JVM, JRE, JDK?

A:

- JVM: runs bytecode.
- JRE: JVM + libraries to run programs.
- JDK: JRE + development tools like javac.

Memory line: JDK = JRE + tools.

### 3) Q: What is bytecode? Why Java is platform independent?

A: Java source code compiles into bytecode (.class). Any system with JVM can run it.
So same code works on Windows, Linux, Mac.

### 4) Q: Define class and object with example.

A: Class is blueprint, object is real instance of class.

Example:

```java
class Car {
    void start() {
        System.out.println("Start");
    }
}
Car c = new Car();
c.start();
```

### 5) Q: What is constructor?

A: Constructor initializes object. It has same name as class and no return type.

Example:

```java
class Student {
    Student() {
        System.out.println("Object created");
    }
}
```

### 6) Q: Variable vs constant?

A: Variable value changes. Constant value does not change and uses final.

Example:

```java
int age = 20;
final double PI = 3.14;
```

### 7) Q: Explain array and operators.

A: Array stores same type values. Operators perform operations.

Example:

```java
int[] marks = {70, 80, 90};
int sum = marks[0] + marks[1];
```

### 8) Q: Explain if-else and loop.

A: if-else is decision statement. Loop repeats code.

Example:

```java
if (age >= 18) System.out.println("Adult");
for (int i = 1; i <= 3; i++) System.out.println(i);
```

## Last Revision ✅

- JVM, JRE, JDK
- Bytecode and platform independence
- Class, object, constructor
- if-else, loop, array
