# Spring Boot Project - First Web Application

## Project Description
This project demonstrates the creation of a Spring Boot web application, including:
- Building a project using Spring Initializr,
- Writing a basic controller,
- Handling HTTP GET requests,
- Displaying dynamic HTML views using Thymeleaf.

---

## Application Features

1. **Home Page (`/`)**
    - Displays a text message:
      ```
      Hello Vistula, in my first Spring controller.
      ```
    - **Example URL**:
      ```
      http://localhost:8080/
      ```

2. **Greeting Page (`/greeting`)**
    - Accepts an optional `name` parameter and displays a personalized message:
        - **Example URL**:
          ```
          http://localhost:8080/greeting?name=Vistula
          ```
        - Output:
          ```
          Hello, Vistula!
          ```

3. **HTML View (`greeting.html`)**
    - Displays a dynamic message and an image of the **Vistula University** logo.

---

## Project Structure

```plaintext
first-project-java-spring/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── pl/edu/vistula/first_project_java_spring/
│   │   │       ├── controller/
│   │   │       │   ├── HelloController.java       
│   │   │       │   └── TextController.java        
│   │   │       └── FirstProjectJavaSpringApplication.java  
│   │   └── resources/
│   │       ├── static/images/
│   │       │   └── vistula.png                    
│   │       ├── templates/
│   │       │   └── greeting.html                  
│   │       └── application.properties             
│
└── README.md                                       
