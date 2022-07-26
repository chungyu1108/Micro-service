GOAL
Refactor our old webpage interface to achieve better conversion and interaction on the login page with users.

Basically, when the user request the service from the webpage, my microservice manages its own data to the microservices principle. A single data store shouldn't be shared by two services. Instead, each service is in charge of maintaining its own private data stores, which other services are unable to directly access. Therefore, when the user request the ask question, first the server will find the answer and explanation for the database, than if the database did’t have the answer, the server will sent the request to the expert for the response.
