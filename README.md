To - Do List - Spring Boot Project
 
📋 Project Overview

This is a To-Do List application built with Spring Boot. The project provides a RESTful API to manage tasks, allowing users to create, update, retrieve, and delete to-do items. 15651.

🚀 Technologies Used

Java
Spring Boot
Spring Data

H2 Database (in-memory for development)
Lombok - for reducing boilerplate code

Maven - Build too
🧩 Project Structure

├── src
│   ├── main
│   │   ├── java
│   │   │   └── net.javaguides.todo
│   │   │       ├── controller  # REST controllers
│   │   │       ├── dto         # Data Transfer Objects (DTOs)
│   │   │       ├── entity      # JPA entities
│   │   │       ├── repository  # Data access layer
│   │   │       └── service     # Business logic
│   │   └─-─ resources
│   │       └── application.properties # Configuration
├── pom.xml  - # Project dependencies
└── README.md       

🔧 Setup Instructions

Clone the repository:

git clone https://github.com/ertugrulgaripardic/To-Do-List-Spring-Boot.git

Navigate to the project directory:

cd To-Do-List-Spring-Boot

Build the project:

mvn clean install

Run the application

mvn spring-boot:run

Access the H2 database console:Visit http://localhost:8080/h2-console and use the credentials in application.properties.

🖥️ API Endpoints

HTTP Method

Endpoint

Description

GET

/api/todos

Get all to-dos

POST
/api/todo

Create a to-do

GET

/api/todos/{id}

Get to-do by ID

PUT
/api/todos/id

Update to-do - 

DELETE /api/todos/{id}

Delete to-do

📝 Example To-Do JSON

{
  "title": "Complete Spring Boot project",
  "description": "Finish coding and update README",
  "completed": false
}

📢 Acknowledgements

This project was created by Ertuğrul Garipardıç as part of a learning exercise in Spring Boot and RESTful API development.

🏆 License

This project is open-source and available under the MIT License.

