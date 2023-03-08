# Project org.simple.employeeclient

Steps to run this project:

1. Download OpenJDK 17.0.2 -> https://jdk.java.net/archive/
1. Add Java Path : <JDK unzipped path>\bin
1. Download Maven 3.9.0 -> https://maven.apache.org/download.cgi
1. Add Maven Path : <Maven unzipped path>\bin
1. Build This Repository by Maven command:+ : mvn clean package 
1. Download Payara Micro 6.2023.2 -> https://www.payara.fish/downloads/payara-platform-community-edition/
1. java -jar payara-micro-6.2023.2.jar --deploy payara5\glassfish\domains\domain1\autodeploy\EmployeeClient-1.0.war --port <port>