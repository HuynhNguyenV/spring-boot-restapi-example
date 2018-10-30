# [spring-boot-restapi-example](https://www.callicoder.com/spring-boot-rest-api-tutorial-with-mysql-jpa-hibernate/)
Mysql
````mysql
  CREATE DATABASE  IF NOT EXISTS `notes_app`;
  USE `notes_app`;
    
  CREATE TABLE `notes_app`.`notes` (
      `id` INT NOT NULL AUTO_INCREMENT,
      `title` VARCHAR(45) NULL,
      `content` VARCHAR(255) NULL,
  PRIMARY KEY (`id`));
```` 
- @Configuration : Any class annotated with @Configuration annotation is bootstrapped by Spring and is also considered as a source of other bean definitions.
- @EnableAutoConfiguration : This annotation tells Spring to automatically configure your application based on the dependencies that you have added in the pom.xml file.
- @ComponentScan : It tells Spring to scan and bootstrap other components defined in the current package (com.example.easynotes) and all the sub-packages.



     
