# CICD_Java_app

This application is java spring boot web application  

Developed a CI/CD pipeline using Jenkins, Docker, Kubernetes, and Helm to automate Java application deployment on Kubernetes cluster.
Implemented static code analysis with Sonarqube and secured artifact management through Nexus for streamlined and efficient software release

build tool is ** gradle **

when we build the code using command ```./gradlew build ``` it will generate war file. that war can be placed in tomcat server to see application web page

code is integrated with sonarqube plugin which help us in static code analysis 

``` ./gradlew sonarqube ```
