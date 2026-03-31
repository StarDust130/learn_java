# Unit 4 README 📦

## Most Important Q&A (Write In Exam) ⭐

### 1) Q: What are Java I/O streams?

A: Streams are used to read and write data.
Two main types: input stream and output stream.

### 2) Q: Byte stream vs character stream?

A:

- Byte stream handles binary data (InputStream, OutputStream).
- Character stream handles text data (Reader, Writer).

Example:

```java
import java.io.*;
FileInputStream in = new FileInputStream("a.txt");
int data = in.read();
in.close();
```

### 3) Q: What is package? How to import?

A: Package is collection of related classes.
Import is used to use classes from package.

Example:

```java
import java.util.Scanner;
```

### 4) Q: What is AWT?

A: AWT (Abstract Window Toolkit) is Java GUI library for windows, buttons, text fields.

Example:

```java
import java.awt.*;
Frame f = new Frame("Demo");
f.setSize(300, 200);
f.setVisible(true);
```

### 5) Q: What is event handling?

A: Event handling responds to user actions like mouse click and key press.

### 6) Q: Listener and adapter class?

A:

- Listener: interface to handle event.
- Adapter class: helper class with default methods for listeners.

### 7) Q: Socket and ServerSocket?

A:

- Socket: used by client.
- ServerSocket: used by server to accept client connection.

### 8) Q: What is URL connection?

A: URL connection is used to connect and read data from web resource.

## Last Revision ✅

- byte vs character stream
- package and import
- AWT and event handling
- socket and server socket
