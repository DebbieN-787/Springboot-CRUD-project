# Springboot-CRUD-project

In my latest project, I developed a Spring Boot CRUD application specifically designed for managing student data. I took charge of creating the entire application from scratch, focusing on a few key components:

-Application: I wrote the main method to bootstrap the Spring Boot application, ensuring a smooth startup and integration of all components.

-Controller: I developed the controller class to handle HTTP requests related to student data. This involved creating endpoints for creating, reading, updating, and deleting student records.

-Entity: I defined an entity class for 'Student', mapping it meticulously to the corresponding SQLite database table to store student information effectively.

-Repository: I created the repository interface to facilitate smooth communication between the application and the SQLite database, using Spring Data JPA for efficient database operations.

--SQLiteDialect: I customized the SQLite dialect settings to optimize the database interactions, tailoring it to the specific needs of the student data management.

Service: Here, I implemented the business logic for handling student data, ensuring robust and error-free processing of CRUD operations.

-Properties.file: In the properties file, I configured the SQLite database details, ensuring a seamless connection and operation of the application.
-POM.xml: I meticulously set up the Maven POM file, including all necessary dependencies and configurations for the Spring Boot framework and the SQLite database.




Finally, I rigorously tested all the CRUD operations for student data using Postman. This helped me validate the functionality of each endpoint, ensuring they worked correctly with the SQLite database. The project was a significant step in my journey as a developer, blending my skills in Spring Boot development, database management, and API testing.
