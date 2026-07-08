Servlet RequestDispatcher Demo
📌 Description
This project demonstrates communication between two Java Servlets using RequestDispatcher.forward(). The first servlet calculates the sum of two numbers and forwards the request to the second servlet, which calculates the square of the result.
🚀 Technologies Used
Java
Servlets
HTML
Apache Tomcat
Eclipse IDE
📂 Project Structure
AddServlet.java
SqServlet.java
index.html
web.xml
⚙️ How It Works
User enters two numbers in the HTML form.
AddServlet receives the request.
It calculates the sum of the two numbers.
The sum is stored using:
request.setAttribute("k", k);
The request is forwarded to SqServlet using:
RequestDispatcher.forward(request, response);
SqServlet retrieves the value using:
request.getAttribute("k");
The square of the sum is displayed in the browser.
