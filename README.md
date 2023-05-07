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

`curl --location 'http://localhost:8080/api/auth/signup' \
--header 'Content-Type: application/json' \
--header 'Authorization: Bearer eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJyYWRhbjIubmd1eWVuQG5hYi5jb20uYXUiLCJpYXQiOjE2ODMxMTIxOTIsImV4cCI6MTY4MzEyMDU5Mn0.dUDzqOw2shQwqeY0JtJS7uyJEDVPMLiX4Ktso-H5lSJRq8lTY77DN337LIhexz5cyt1e6UODA4i-IBip9KHOWQ' \
--data-raw '{
"email": "admin@upgrad.com",
"password": "Admin@123",
"firstName": "Admin",
"lastName": "Upgrad",
"contactNumber": "0939123456",
"role": ["admin"]
}'`