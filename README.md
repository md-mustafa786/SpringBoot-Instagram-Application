# SpringBoot-Instagram-Application
 In this project, we have created a Spring Boot application for a simple Instagram-like platform. The application has two entity classes: User and Post. The User class contains user details such as username, age, phone number, email, and password. The Post class contains details about each post, including post name, description, and the user who posted it.

We have implemented CRUD operations for the User class, including user sign up, login, and updating user details. We have also implemented a method for creating a new post and associating it with a user.

We have added validation for email, password fields to ensure that only valid data is stored in the database.

Overall, this project demonstrates the use of Spring Boot, Maven, and JPA to build a simple social media application.
##  Framework and Language use in this Project-
 *  Springboot
 *  Java
##  Dependencies
 *  Spring Web
 *  MySQL Database
 *  Spring Boot DevTools
 *  Lombok 
 *  Spring Data JPA
 
### Requirments
 * IntelliJIDEA
 * Serverport: 8080 (use: localhost:8080)
 * Java version: 17
 * Everything is present in the pom.xml (no need to download any library)
### Steps to run Application
 * Download the source code and import in intellijIDEA.
 * Go to localhost:8080/
 * Type endpoints 
 * If need then provide RequestBody in json format and Path-variable or path-param.
 ## There are two Models-
 * User
 * Post
## User will perform following operations - 
 ##### 1) - Add User Info -
* In this functionality we are save user details - 
 ##### -> Add User EndPoints:
       * Home - localhost:8080/
       * Endpoint -/add-user

 
 ##### 2) - Get an User Info by Id  or All User Details-
* In this functionality We get one user info. by sending the user-id in url through Postman @Nullable @RequestParam. If I am not passing any user-id then this functionality get all User Details - 
  ##### -> EndPoints:
       * Home - localhost:8080/
       * Endpoint - /get-user
 
 
 ##### 3) - Update User Details -
* In This functionality user can update our old details through old user-id - 
 ##### -> EndPoints:
       * Home - localhost:8080/
       * Endpoint - /update-user/{userId}
 
 ## Post Model will perform following operations - 
 ##### 1) - Add Post Info-
* This functionality saved  Post details - 
 ##### -> EndPoints:
       * Home - localhost:8080/
       * Endpoint -/add-post
 
 

 ##### 2) - Get all Post detils -
 * This functionality get all Post details of User by providing user Id and Also we can find a particular post of user by providing userId and  postId in @RequestParam -
 ##### -> EndPoints:
       * Home - localhost:8080/
       * Endpoint -/get-post
 


##### 2) - Update Post detils -
 * This functionality we can update our Post details by postId-
 ##### -> EndPoints:
       * Home - localhost:8080/
       * Endpoint -/update-post/{postId}


### Note
* You can change server port by application.properties file i.e.

        server.port=8081
