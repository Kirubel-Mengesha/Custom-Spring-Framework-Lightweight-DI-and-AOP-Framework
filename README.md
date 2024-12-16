# Custom Spring Framework: Lightweight DI and AOP Framework  

## Overview  
This repository contains a custom-built lightweight Spring-like framework designed to mimic the core features of the Spring Framework, including dependency injection (DI), aspect-oriented programming (AOP), scheduling, and more. The framework is implemented as part of an academic project for Advanced Software Development (ASD).  

The project involves creating a modular framework with core functionalities and building a sample application to demonstrate its capabilities.  

---

## Features  
### Framework Capabilities  
1. **Dependency Injection**  
   - Field injection using `@Autowired`.  
   - Injection by name with `@Qualifier`.  
   - Setter and constructor injection.  

2. **Value Injection**  
   - Use the `@Value` annotation to inject properties from an `application.properties` file.  

3. **Application Class**  
   - Mimics the Spring Boot-style application runner using `FWApplication.run()`.  

4. **Profiles**  
   - Support for profiles similar to Spring Boot's profile system.  

5. **Scheduling**  
   - Basic scheduling with the `@Scheduled` annotation.  
   - Cron-based scheduling for fine-grained control.  

6. **Event Handling**  
   - Publish-subscribe mechanism for event-driven programming using `@EventListener`.  

7. **Configuration Properties**  
   - Map related properties from the `application.properties` file using the `@ConfigurationProperties` annotation.  

8. **Asynchronous Methods**  
   - Enable asynchronous execution with the `@Async` annotation.  

9. **Aspect-Oriented Programming (AOP)**  
   - Basic AOP with `@Before` and `@After` annotations.  
   - Advanced AOP with `@Around` annotations for method interception.  

---
