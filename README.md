## Dependency Management Exercise
The repo contains a spring boot application with a single `/api/v1/fixme` endpoint

### Objectives
1. Fix the build issues and run the application
2. The build should be clean without warnings and application should run using wrapper files
3. `/api/v1/fixme` should return ``{ response: "Good Job, you win !!!" }``

### HINTS
1. Transitive vs Direct Dependencies
2. Target Java version 
3. Spring Boot Maven Plugin 
4. Shading a maven dependency
5. ClassNotException
6. Maven Scope for local dependencies 
7. Maven wrapper
8. Maven central repository

### References
1. https://maven.apache.org/guides/introduction/introduction-to-dependency-mechanism.html
2. https://docs.spring.io/spring-boot/docs/current/maven-plugin/reference/html/
