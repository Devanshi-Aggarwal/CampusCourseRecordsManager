Campus Course & Records Manager (CCRM)
Project Overview
The Campus Course & Records Manager (CCRM) is a console-based Java application designed to manage student and course data for an academic institution. This project was developed as a Java SE application to demonstrate proficiency in core Java concepts, object-oriented programming (OOP), modern file I/O, and common design patterns.

The application allows users to:

Manage Students: Add, list, and update student records.

Manage Courses: Add, list, and manage course data.

Handle Enrollment & Grades: Enroll students in courses, record grades, and generate transcripts.

Perform File Operations: Import/export data from simple CSV files and create timestamped backups.

Setup and Installation
Java Environment
This project was developed using Java Development Kit (JDK) 21. To run it, you must have JDK 21 installed and configured on your system.

1. JDK/JRE/JVM Architecture:

JDK (Java Development Kit): The full development environment that includes the JRE and all the tools for compiling, debugging, and running Java applications.

JRE (Java Runtime Environment): The core component that provides the necessary libraries and the JVM to run Java applications.

JVM (Java Virtual Machine): The abstract machine that executes Java bytecode. It is the component that makes Java "write once, run anywhere."

2. Java ME vs. Java SE vs. Java EE:



Java ME

Java SE

Java EE

Purpose

Embedded, mobile devices

Desktop, general-purpose applications

Large-scale enterprise applications

Example

Old mobile phone apps

This CCRM application

Web servers, enterprise platforms

Key APIs

Small-footprint APIs

java.lang, java.io, java.util

Servlets, JPA, EJBs

Running the Application
Open in Eclipse: Open this project in Eclipse IDE.

Ensure JDK 21 is configured: Right-click the project in Package Explorer, go to Properties > Java Build Path, and ensure the JRE System Library is set to JavaSE-21.

Run: Right-click the Main.java file in edu.ccrm.cli and select Run As > Java Application. The program will start in the console.

Project Features and Demonstrations
This project demonstrates several mandatory technical requirements from the project brief.

Syllabus Topic

File/Class/Method Where it's Demonstrated

Encapsulation

Person.java (private fields with public getters)

Inheritance

Student.java and Instructor.java (extending Person)

Abstraction

Person.java (abstract class and method)

Polymorphism

Student.java and Instructor.java (overriding getDetails())

Singleton Pattern

AppConfig.java (getInstance() method)

Builder Pattern

Course.java (nested Builder class)

Enums with Fields

Grade.java (with gradePoint field and constructor)

Modern I/O (NIO.2)

ImportExportService.java, BackupService.java

Recursion

BackupService.java (in getDirectorySize() method)

Custom Exceptions

DuplicateEnrollmentException, MaxCreditLimitExceededException

java.time API

Student.java (using LocalDate for enrollment date)

Arrays & String Methods

Main.java (parsing input, using split() and join())