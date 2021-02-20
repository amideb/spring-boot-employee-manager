# spring-boot-employee-manager

---> Single page website to store, update, delete employee information from the database.

---> Here for the frontend, I use Angular, and Spring Boot as the backend and MySQL for the database.

---> In my backend API, I have a model or entity to hold the employee attributes. Have a repository to access the database, extended by JpaRepository. And, service to implements all the business logic to manage the employee operations. A controller to maps requests and handles them and calls the service if needed.
For the database, MySQL database has been used and connected with the backend through the application.properties.

---> I have checked the HTTP requests on this API with Postman.

---> In the Angular part, also have a model which holds the employee attributes. Have service to connect the angular app with backend controller, here I use HttpClientModule and Observable. And the component for the business logic and handle the user requests by the UI.

---> Here I learned about the Cross-origin concept.

---> Technology: Angular, Spring Boot and Spring Rest, MySQL Database, Postman, REST API
