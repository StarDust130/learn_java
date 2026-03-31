# Unit 3 README 🛡️

## Most Important Q&A (Write In Exam) ⭐

### 1) Q: What is exception? Types?

A: Exception is an unwanted event during program execution.
Types: checked exception and unchecked exception.

### 2) Q: Explain try-catch-finally.

A:

- try: risky code
- catch: handles exception
- finally: always runs

Example:

```java
try {
    int x = 10 / 0;
} catch (ArithmeticException e) {
    System.out.println("Cannot divide by zero");
} finally {
    System.out.println("Done");
}
```

### 3) Q: throw vs throws?

A:

- throw: used inside method to throw exception.
- throws: used in method declaration.

Example:

```java
void test() throws Exception {
    throw new Exception("Error");
}
```

### 4) Q: What is user-defined exception?

A: Custom exception created by programmer by extending Exception class.

### 5) Q: What is thread? Why multithreading?

A: Thread is smallest unit of process.
Multithreading improves performance by doing multiple tasks.

### 6) Q: Explain thread lifecycle.

A: New -> Runnable -> Running -> Waiting/Blocked -> Dead.

### 7) Q: What is thread priority?

A: Priority tells scheduler which thread gets more CPU chance.

### 8) Q: What is synchronization?

A: Synchronization controls shared resource access by one thread at a time.

Example:

```java
class MyThread extends Thread {
    public void run() {
        System.out.println("Thread running");
    }
}
```

## Last Revision ✅

- try-catch-finally
- throw vs throws
- thread lifecycle
- synchronization meaning
