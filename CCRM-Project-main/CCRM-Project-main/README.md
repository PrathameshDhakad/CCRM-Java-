# Campus Course & Records Manager (CCRM)

Welcome to the Campus Course & Records Manager (CCRM), a powerful Java console application designed to
streamline academic administration.This tool provides a robust way to manage students, courses,
 enrollments, and grades within an educational setting.

## Features
This application is built with a comprehensive set of features to handle all your record-keeping needs:
- User Management: Add, update, and manage student and instructor data with ease.
- Course Management: Create, search, and modify courses, and assign them to specific instructors and 
  departments.
- Smart Enrollment: Enroll and unenroll students while adhering to key business rules, such as enforcing  
  maximum credit limits per semester.
- Grade Reporting: Accurately record and calculate student grades and GPAs, with the ability to generate
  a detailed transcript.
- File Handling: Seamlessly import and export data using simple CSV files. The application also includes 
  a reliable backup feature using the modern NIO.2 API.

## Evolution of Java

- 1995: Java 1.0 released by Sun Microsystems
- 1997: Java 1.1 with JDBC, RMI, and reflection
- 2000: Java 1.3 with HotSpot JVM
- 2004: Java 5 with generics, annotations, autoboxing
- 2014: Java 8 with lambdas, streams, new date/time API
- 2017: Java 9 with module system
- 2018: Java 11 as LTS version
- 2021: Java 17 as current LTS version
- 2023: Java 21 with virtual threads

## Java Platforms Comparison
___________________________________________________________________________________________________________________
| Platform | Full Name         | Purpose                         | Key Features                                   |
|----------|-------------------|---------------------------------|------------------------------------------------|
| Java SE | Standard Edition   | Desktop and server applications | Core Java libraries, JVM, development tools    |
| Java EE | Enterprise Edition | Enterprise applications         | Servlets, JSP, EJB, JMS (now Jakarta EE)       |
| Java ME | Micro Edition      | Mobile and embedded devices     | Limited libraries for constrained environments |
|_________|____________________|_________________________________|________________________________________________|

## Java Architecture

- **JDK (Java Development Kit)**: Development environment including compiler, debugger, and other tools
- **JRE (Java Runtime Environment)**: Runtime environment for executing Java applications
- **JVM (Java Virtual Machine)**: Executes Java bytecode, provides platform independence

The JDK contains the JRE, which contains the JVM. Developers use the JDK to create applications, which run on the JRE using the JVM.

## Installation on Windows

1. Download JDK from Oracle's website
2. Run the installer and follow the instructions
3. Set JAVA_HOME environment variable to JDK installation path
4. Add %JAVA_HOME%\bin to PATH environment variable
5. Verify installation with `java -version` in command prompt

## Eclipse IDE Setup

1. Download Eclipse IDE for Java Developers
2. Extract to a folder and run eclipse.exe
3. Create a new Java project
4. Configure JDK in project properties
5. Create packages and classes as needed

## How to Run

1. Clone the repository
2. Compile with `javac -d bin src/**/*.java`
3. Run with `java -cp bin edu.ccrm.Main`

## Enabling Assertions

Add `-ea` flag when running the application: