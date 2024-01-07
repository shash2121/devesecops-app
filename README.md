#Unit Tests
- mvn test runs the basic tests on the code based on the test cases mentioned in the src/test directory.
- All test cases need to pass.

#Jacoco (Java Code Coverage)
- Used to measure how many lines of the code are tested
- Shows in form of graph
- In order to use it in the jenkins pipeline, changes need to be done in the pom.xml

# docker run -d --name sonarqube -e SONAR_ES_BOOTSTRAP_CHECKS_DISABLE=true -p 9000:9000 sonarqube:latest

#Sonarqube: 
  - Helps is detecting areas in code that need refactoring
  - Helps in finding bugs and vulnerabilties
  - Highlights the line with issues
  - quality gate is used to ensure code standards are met in projects