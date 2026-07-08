# Servlet RequestDispatcher Demo

A Java Servlet project that demonstrates inter-servlet communication using **RequestDispatcher.forward()**. The application accepts two numbers from the user, calculates their sum in one servlet, forwards the request to another servlet, and displays the square of the result.

## 🚀 Features
- Accepts user input through an HTML form
- Uses `RequestDispatcher.forward()` for servlet communication
- Passes data using `request.setAttribute()`
- Retrieves data using `request.getAttribute()`
- Displays the final result in the browser

## 🛠️ Technologies Used
- Java
- Java Servlets
- HTML
- Apache Tomcat
- Eclipse IDE

## 📁 Project Structure
```text
src/
├── AddServlet.java
├── SqServlet.java
├── index.html
└── WEB-INF/
    └── web.xml
```

## ▶️ Workflow
```
HTML Form
     │
     ▼
AddServlet
     │
request.setAttribute()
     │
RequestDispatcher.forward()
     │
     ▼
SqServlet
     │
Displays Result
```

## 📚 Concepts Covered
- RequestDispatcher
- Servlet Communication
- HttpServletRequest
- HttpServletResponse
- Request Attributes
