# Simple Spring Demo [![Build Status](https://travis-ci.org/mr-test/Spring-MVC-4-Demo.svg?branch=master)](https://travis-ci.org/mr-test/Spring-MVC-4-Demo)
 
### Requariment 
    1. Java JDK (SE 8)
    2. Maven (3.2.0 +)
    
### Technologies :
    1. Spring (4.1 +)
    2. Gson (2.8 +)
    3. Log4j (1.2 +)
    
### Testing Tools :
    1. JUnit: test runner
    2. MockMVC: testing Spring MVC controllers
    3. Hamcrest Matchers: assertions
        
 
### Building from Source

  - Checkout the source code from by running
   
        -  $ git clone https://github.com/mr-test/Spring-5.git
    
  - Navigate into the cloned repository directory , And (Compile , installed) maven dependency:
   
        -  $ cd Spring-5
        -  $ mvn clean install
    
### To run the application:
   Running Tomcat 7 servlet container :
   
        -  $ mvn tomcat7:run-war
        
Access the deployed web application at : http://localhost:8080/Spring5/ will return an initial response.
### To run the test cases:

        -  $ mvn clean test

