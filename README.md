# WebApplicationSecurity
Secure Software Development course assignment - fix and analyze the security vulnerabilities within a given implementation of a Web application representing a food ordering website. 

The assignment details are available in Serbian under the RBS_Projekat_2021_2022.pdf PDF document.

The application itself is implemented using Spring Framework and Maven. 
The application uses H2 Java SQL Database for storing data about users, restaurants, orders, ordered items, deliveries etc.

There are the following types of users:
  - customers
  - restaurants
  - admins
  
The assignment contains the following tasks:
  - 1. Use SonarQube for static code analysis of the Web application and see if the detected security issues are true or false positives (the result of this task can be seen within the SonarQube izvestaj.docx document).
  - 2. SQL Injection - perform an SQL Injection based attack on the food ordering page for users and use it to insert a new restaurant within the Web application database (the results of this task can be seen within the Attacks/SQLi.txt - the instructions are written in Serbian) and implement an application wide SQL Injection protection.
  - 3. Cross-site request forgery (CSRF) and Cross-site scripting (XSS) - perform a combination attack using CSRF/CSS in the username/password change form so it changes the username/password for user ID 1, using a POST request (the result of this task can be seen within the Attacks/csrf-exploit folder, within the index.html page - a user only needs to be logged in and if they visit the mentioned malicious page and click the YOU WIN image, they will be used to perform the attack) and implement an application wide CSRF and XSS protection.
  - 4. Implement application wide authorization (the entire table can be seen in section 5 of the RBS_Projekat_2021_2022.pdf document) using Spring Security and Thymeleaf concepts, so that only the users with appropriate roles can access appropriate functionalities of the Web application.
  - 5. DevOps - implement proper exception handling and logging which could be useful in an attack scenario to find the culprit and action auditing.
 
  
  

