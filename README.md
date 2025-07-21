# WebBankApp
A web bank app similar to CIBC.

## Description
A web bank app for my Porfolio. This web bank app will be cimilar to CIBC.

## Step Took
1. Requirements & Planning
   
   **Core Feautures**
   | User registration & login (secure auth) | Account dashboard | Check account balance | Transfer money between accounts | Transaction history |
   |-----------------------------------------|-------------------|-----------------------|---------------------------------|---------------------|
   
   **Security Feautures**
   | HTTPS/ JWT Authentication /Session | Form validation (client + server-side) | Password hashing |
   |------------------------------------|----------------------------------------|------------------|
   
   **Tech Stack**
   | Layer        | Technology |
   |--------------|------------|
   | Frontend | HTML/CSS/JS |
   | Backend | Java, Spring Boot|
   | DataBase | MySQL |
   | CI/CD | GitHub Actions
<img width="624" height="143 Feedback" alt= + Docker |

2. Started with simple Class Diagram"image" src="https://github.com/user-attachments/assets/7cc12f45-8f0f-404b-837d-2453be43b3d1" />

3. Created my SpringBoot Maven java project.
   **Dependency Added**
   - Spring Web
   - Spring Data JPA
   - Spring Security
   - Spring Boot DevTools
   - MySQL
   - Thymeleaf
   - Validation

4. -- In my MySQL workbench I have created my 'baking_app_db' database table
5. Updated my app.properties; Spring DB config, JPA config and Thymeleaf. 
6. Created my Model Architecture Class; Account, Transaction and User. Added appropriate jpa annotations. 
7. Added Enum class with USER and ADMIN role. 
8. Added RegisterDTO and LoginDTO
9. 