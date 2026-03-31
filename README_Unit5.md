# Unit 5 README 🌐

## Most Important Q&A (Write In Exam) ⭐

### 1) Q: What is servlet?

A: Servlet is a Java program that runs on web server and handles client request.

### 2) Q: Explain servlet lifecycle.

A: Three main methods:

- init() called once
- service() called for each request
- destroy() called once before removal

Example:

```java
public void init() {}
public void service() {}
public void destroy() {}
```

### 3) Q: GenericServlet vs HttpServlet.

A:

- GenericServlet: protocol independent.
- HttpServlet: works for HTTP methods like doGet and doPost.

### 4) Q: What are request and response objects?

A:

- Request object has client data.
- Response object sends output back to client.

### 5) Q: What is JDBC? Why used?

A: JDBC means Java Database Connectivity. It connects Java program with database.

### 6) Q: JDBC architecture/API (short).

A: Java app uses JDBC API -> DriverManager -> JDBC Driver -> Database.

### 7) Q: JDBC steps to connect database.

A:

1. Load driver
2. Make connection
3. Create statement
4. Execute query
5. Close connection

Example:

```java
Class.forName("com.mysql.cj.jdbc.Driver");
Connection con = DriverManager.getConnection(
    "jdbc:mysql://localhost:3306/test", "root", "pass"
);
Statement st = con.createStatement();
ResultSet rs = st.executeQuery("select * from student");
con.close();
```

### 8) Q: Web server vs IDE examples.

A:

- Web server: Apache Tomcat, JBoss
- IDE: Eclipse, NetBeans

## Last Revision ✅

- servlet lifecycle
- GenericServlet vs HttpServlet
- request and response
- JDBC full form and steps
