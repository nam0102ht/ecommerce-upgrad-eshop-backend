# Getting Started with Ecommerce Upgrad Backend

Application and environment were related to this app includes:
 - [Java](https://www.oracle.com/cis/java/technologies/downloads/#java20)
 - [Docker](https://www.docker.com/)
 - [Spring boot](https://spring.io/)

### The way is running this app
 
Running by your commandline:

Run local environment for integration
`docker-compose up -d`

Run this app:

For linux:
`./mvnw spring-boot:run`

For window:

[Please download and install maven follow this page](https://maven.apache.org/)

`mvn spring-boot:run`

### Sign up the admin

Run curl command in your cmd when starting the project complete

`curl --location 'http://localhost:8080/api/auth/signup' \
--header 'Content-Type: application/json' \
--data-raw '{ "email": "admin@upgrad.com", "password": "Admin@123", "firstName": "Admin", "lastName": "Upgrad", "contactNumber": "0939123456", "role": ["admin"] }'`

#### Or Sign up the admin by postman at [here](https://github.com/nam0102ht/ecommerce-upgrad-eshop-backend/tree/develop/postman)
