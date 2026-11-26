# Git Repository Link
- order-management-fulfillment-platform : https://github.com/DheerajGk21/order-management-fulfillment-platform

# Start the project

### Bring up Infrastructure

1. Run : `>> docker comnpose up -d`
2. Verify : `>> docker ps`. You should see container `omfp-postgres` running.


### Add a SpringBoot Microservice

1. Go to https://start.spring.io/
2. Configurations :
   1. Project : Maven
   2. Language : Java
   3. SpringBoot : 4.2.0
   4. Group : com.omfp
   5. Artifact : name-service (Ex. product-service)
   6. Package Name : com.group_name.artifact_name (Ex. com.omfp.product-service)
   7. Packaging : JAR
   8. Configuration : YAML
   9. Java : 21


3. Add Dependencies 
    1. Spring Web
    2. Spring Data JPA 
    3. PostgreSQL Driver 
    4. Validation 
    5. Spring Boot Actuator 
    6. Flyway Migration
