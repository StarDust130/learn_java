# Unit 1 - Java Quick Notes 🚀

## 1) Overview of Java 🌍

- Java = popular programming language for apps, web, and software.
- **Genesis** = Java was made by Sun Microsystems.
- **History** = Created in 1995, now maintained by Oracle.

⭐ **Important for exam:** Why Java is popular -> **Write once, run anywhere**.

## 2) JVM, JDK, JRE ⚙️

- **JVM** (Java Virtual Machine): Runs Java bytecode.
- **JDK** (Java Development Kit): Tools to write + compile Java (`javac`).
- **JRE** (Java Runtime Environment): Runs Java programs (`java`).

✅ Easy memory trick:

- JDK = JRE + development tools.

## 3) Source File, JAR, Compile & Run 📁

- **Source file** = `.java` file (example: `Hello.java`).
- **JAR file** = Java archive file (`.jar`) to package classes.

### Compile and Run

```bash
javac Hello.java
java Hello
```

⭐ **Important:**

- `javac` -> converts `.java` to `.class` (bytecode)
- `java` -> runs bytecode using JVM

## 4) Bytecode & Platform Independence 🔁

- Java code compiles to **bytecode**.
- Bytecode runs on any OS with JVM.
- That is why Java is **platform independent**.

Example:

- Same `.class` file works on Windows/Linux/Mac (if JVM exists).

## 5) Data Types, Literals, Variables, Constants 🔢

- **Data types**: `int`, `float`, `double`, `char`, `boolean`, etc.
- **Literal**: direct value (example: `10`, `'A'`, `true`, `"Hi"`).
- **Variable**: value can change.
- **Constant**: value cannot change (`final`).

Example:

```java
int age = 20;           // variable
final double PI = 3.14; // constant
```

⭐ **Important:** `final` keyword for constant.

## 6) Arrays & Types 📚

- Array stores many values of same type.
- Types:
  - 1D array
  - 2D array

Example:

```java
int[] marks = {80, 90, 85};
int[][] mat = {{1, 2}, {3, 4}};
```

## 7) Operators ➕➖

- Arithmetic: `+ - * / %`
- Relational: `== != > < >= <=`
- Logical: `&& || !`
- Assignment: `= += -=`

⭐ **Important:** Difference between `=` and `==`.

## 8) Conditional & Looping Statements 🔀

- Conditional: `if`, `if-else`, `switch`
- Loops: `for`, `while`, `do-while`

Example:

```java
if (age >= 18) {
	System.out.println("Adult");
}

for (int i = 1; i <= 3; i++) {
	System.out.println(i);
}
```

## 9) Packages 📦

- Package = group of related classes.
- Helps organize code.

Example:

```java
import java.util.Scanner;
```

## 10) Class, Object, Method 🧱

- **Class** = blueprint.
- **Object** = real instance of class.
- **Method** = function inside class.

Example:

```java
class Car {
	void start() {
		System.out.println("Car started");
	}
}
```

## 11) Nested Class & Inner Class 🪆

- **Nested class** = class inside another class.
- **Inner class** = non-static nested class.

⭐ **Important:** Basic definition is usually asked in short answers.

## 12) String Handling 🔤

- `String` is used to store text.
- Common methods: `length()`, `charAt()`, `substring()`, `equals()`.

Example:

```java
String name = "Java";
System.out.println(name.length());
```

## 13) Constructor 🛠️

- Constructor initializes object.
- Same name as class.
- No return type.

Example:

```java
class Student {
	Student() {
		System.out.println("Object created");
	}
}
```

## 14) Simple Java Program ✅

```java
class Hello {
	public static void main(String[] args) {
		System.out.println("Hello, Java!");
	}
}
```

## Last-Minute Revision (Most Important) 🎯

- JVM vs JDK vs JRE
- Compile vs Run (`javac` vs `java`)
- Bytecode + platform independence
- Data types, variable vs constant (`final`)
- Arrays, operators, loops, conditionals
- Class, object, method, constructor
- Basic string methods
