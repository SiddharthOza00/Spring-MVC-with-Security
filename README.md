# Spring-MVC-with-Security

This project is created using Spring Framework. It uses concepts of Spring Security, JPA/Hibernate and privacy.

The webpage is created with the help of Thymeleaf and using HTML, CSS.

All the passwords are encrypted using "bcrypt" encryption.

To run the project, first execute the SQL scripts and update their location in the application.properties file inside the resources/application.properties directory. Along with that also update the ID, password to access your database.

After completing the above steps, go into main/java/com.security.springboot.demosecurity/DemoSecurityApplication.java and run the code.

After that go to your browser and type in "localhost:8080/". This will take you to the home page where you either add user or use an existing user(check the SQL scripts for existing user) and then you can access different links depending on their role.

Different types of roles are: "EMPLOYEE", "ADMIN", "MANAGER".
