# Cinema-Room-REST-Service
- A simple RESTful service that manage a 9 x 9 movie theater featuring Customers booking, Purchasing, Returning, and Checking statistics
- Developed using Spring Boot framework and tested API endpoints on Postman
- Achieved Object-oriented Programming, handled HTTP requests in controllers, created services and responded with JSON objects
- A project built with tutorials and guildance from [JetBrain Academy - Java Backend Developer Path](https://hyperskill.org/projects/189?track=12)

## Features
1. Show available seats (by GET on "/seats")
2. Allow customers to purchase their tickets (by POST on "/purchase" and assign the ticket with a specific code using UUID)
3. Allow customers to get their tickets refunded (by POST on "/return")
4. Add the movie theater statistics and secure the endpoint with a password (by POST on "/stats")
