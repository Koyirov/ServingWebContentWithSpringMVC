## Serving Web Content with Spring MVC

This guide walks you through the process of creating a 
“Hello, World” web site with Spring.

### What We Will Build

We will build an application that has a static home page 
and that will also accept HTTP GET requests at: http://localhost:8080/greeting.

It will respond with a web page that displays HTML. 
The body of the HTML will contain a greeting: “Hello, World!”

We can customize the greeting with an optional name 
parameter in the query string. The URL might then be 
http://localhost:8080/greeting?name=User.

The name parameter value overrides the default value of 
World and is reflected in the response by the content 
changing to “Hello, User!”

### Dependencies

* **Spring Web**
* **Thymeleaf**
* **Spring Boot DevTools**
