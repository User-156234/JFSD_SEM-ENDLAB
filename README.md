Project Overview:

This Maven-based Spring project demonstrates Constructor Dependency Injection (CDI) and Autowiring with Setter Injection using XML configuration.

Features
CDI for primitive, wrapper, and collection types.
Setter-based Autowiring for establishing relationships between Course and Instructor objects.

Package Structure


src/main/java/com/klef/jfsd/exam/  
│  
├── Employee.java      # Employee class demonstrating CDI.  
├── Course.java        # Course class with setter injection for Instructor.  
└── Instructor.java    # Instructor class to be autowired into Course.  

Configuration Files


src/main/resources/  
└── ApplicationContext.xml  # Spring IoC configuration for CDI and Autowiring.  

Dependencies

Add the following in pom.xml:

xml

<dependency>  
  <groupId>org.springframework</groupId>  
  <artifactId>spring-context</artifactId>  
  <version>5.3.12</version>  
</dependency>  

Running the Application

Clone the repository.
Run ClientDemo.java to test CDI and Autowiring.
Ensure the package structure matches the specified format.

Output
Displays Employee and Course with Instructor details.
