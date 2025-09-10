                                        SamsTrack  
Is a Spring Boot REST API project designed to streamline the process of managing student 
attendance in educational institutions. It allows faculty members to record attendance for 
specific subjects and provides interfaces for viewing and managing these records. The 
primary entities in the system are Students, Subjects, Faculty, and Attendance Records. The 
application aims to reduce paperwork, improve accuracy, and simplify attendance tracking.

Objective: 
✓ Automate attendance tracking through a REST API to streamline integration with 
existing systems. 
✓ Ensure data accuracy with automated validation and storage of attendance records. 
✓ Facilitate seamless integration with educational platforms to enhance faculty and 
administrative workflows. 
Scope of the Project: 
The scope of the SamsTrack project involves developing a REST API to manage student 
attendance, including functionalities for handling Students, Subjects, Faculty, and Attendance 
Records. 

Project Structure :-
Overview of Project Architecture: The project follows a layered architecture pattern, with 
distinct layers for handling different aspects of functionality and data management. 
Layers Description: 
1. Controller Layer: Responsible for handling incoming HTTP requests, processing them, and 
returning appropriate responses. Controllers act as the entry point to the application and 
delegate business logic to the service layer.  
2. Service Layer: Acts as an intermediary between the controller and the data access layer 
(DAO). It contains business logic and orchestrates interactions between different parts of the 
application. Services handle tasks such as validation, data manipulation, and transaction 
management.  
3. DAO (Data Access Object) Layer: Responsible for interacting with the database and 
performing CRUD (Create, Read, Update, Delete) operations on the underlying data. DAOs 
abstract away the details of database interactions and provide a clean interface for the 
service layer to work with.

Responsibilities of each layer: 
• Controller Layer: 
➢ Handle incoming HTTP requests. 
➢ Validate request parameters and payload. 
➢ Invoke appropriate methods in the service layer. 
➢ Format and return HTTP responses. 
• Service Layer: 
➢ Implement business logic and rules. 
➢ Coordinate interactions between controllers and DAOs. 
➢ Perform data manipulation and transformation. 
➢ Manage transactions and ensure data integrity. 
• DAO Layer: 
➢ Provide CRUD operations for accessing and modifying data. 
➢ Translate database queries and commands into appropriate SQL 
➢ statements. 
➢ Handle database transactions and connections. 
➢ Abstract away database-specific details from the service layer.

Used Technology Stack 
✓ Backend Framework: Spring Boot 2.5.6 
✓ Frontend Framework:React 18
✓ Database: MySQL 8 
✓ Database Framework:  Hibernate 5.6 
✓ Java:  JDK 1.8  
✓ Build Tool:  Maven 
✓ Development Environment:  Eclipse 
✓ API Testing Tool:  Postman 

Modules in Project 
1. Student Module  
2. Subject Module  
3. Faculty Module  
4. Attendance Module  
5. User Module 
