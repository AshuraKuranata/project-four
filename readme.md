# Introduction

For my final project in bootcamp, I am tasked to:

*Research job postings for Jr. Web Developer and Jr. Full-Stack Engineer in your area and try to find technology being requested that wasn't covered in this class.  Build a project using as many of these new technologies as you can.*

Based on this requirement, I looked through the course material and the job postings.  Based on my research, I landed on learning:

**Java & Spring (Spring base or Spring Boot)**

My reasoning is that the material that was covered in bootcamp has revolved mainly around weakly typed languages that do not require specific matched specifications while Java requires this in its basic code.

To get started, I needed to install Java into my VM so it would work.  It took some time to develop, but I was ultimately able to complete it using:

https://www.oracle.com/in/java/technologies/downloads/ - Site to download Java file from

https://www.geeksforgeeks.org/download-install-java-windows-linux-macos/ - Tutorial for installation

Ran into some issues, main problem was downloading the incorrect Java application from the site into the system.

# Project Plan/Build

My aim at the completion with the project is to:

| **Feature Aim** | **Description** | **Feature code requirements** |
| :--- | :--- | :--- |
| Program coded in Java | Build back-end utilizing Java and Spring as the primary code base | Java, Spring |
| Front-end/Back-end | Implement a functional, viewable app using Java/Spring that is accessible | Java, Spring, React/Angular? |
| Connect to database with CRUD function | Implement a database with CRUD functionality to this Java/Spring based program | MongoDB or SQL |
| User Authentication  | Implement a secure user authentication program into application | JWT (if using Django/SQL) or OATH2? |
| Professional look | I want to implement a CSS framework (tailwind/bootstrap/other) and use figma models to make the site look professional | Tailwind/Bootstrap, Figma model |

As I work through the initial steps and features as I learn Java, Spring, and how they interact, the features list will develop as I go.


# Learning Java & Spring Boot

Trying to learn a new coding language was a challenge.  Java, being a strongly typed language, has been quite an interesting journey in setting up and determining how to implement as a program.  Some of the major highlights of what I've learned through this process:

### Java
*I utilized the <https://www.w3schools.com/java/default.asp> site to help run through basic lessons and integrate a better understanding of how Java works.*

* Java requires an understanding of the different kinds of methods(or functions), data types, and modifiers that can be utilized in the code.
* Java utilizes classes that house objects within them.  It works akin to the idea that classes are things that can be imported throughout the Java back-end that will allow access to the objects that reside within the class (whether it's data objects or functions).
* Java requires modifiers that define the way that methods or data types are accessed.  A firm understanding of the modifiers is required to best utilize the code.

### Spring Boot
*I utilized <https://medium.com/@alexandre.therrien3/java-spring-tutorial-the-only-tutorial-you-will-need-to-get-started-vs-code-13413e661db5> tutorial to help set up my first intialization of Spring Boot*

* Spring is effectively all the framework code that is pre-created for Java that allows developers to quickly create code related to actions they want to take.
* There's a LOT of different tooling, code, and operations that are within Spring
* In research, I decided to utilize Maven in my implementation of Java Spring Boot to help manage the generated code.  There is another option in Gradle, but for the purposes of learning and the tutorials reviewed, Maven seemed easiest to work with.
* Spring Boot's connections for RESTful APIs to allow connections requires different kinds of annotations to be imported than the Request Mappings that are only for local views.

# Project Results

**Completed Project Work**
* Built Simple High-Low Terminal Game in Java: <https://github.com/AshuraKuranata/high-low-java>
* Created a Java Spring Boot program that connected to PSQL: <https://github.com/AshuraKuranata/spring-psql>
* Implemented a Java Spring Boot program that emulates user authentication and saved login utilizing cookies and csrf:
    * Backend - <https://github.com/AshuraKuranata/userauth>
    * Frontend - <https://github.com/AshuraKuranata/spring-user-auth>

While these projects are not very flashy overall, the work done really helped me get a handle and sense of how Java, Spring Boot, Maven, and how to build a front end like ReactJS to connectt to Java.  There were quite a number of bugs and issues I ran into during the process, including:
* Spring Security & CORS allowances - CORS kept preventing connections between the back and front end
* Utilization of classes and how Java application reads files - I ran into a 3 hr bug fix because the way I implemented Spring Boot was using their boilerplate template, but it required the application file to be reading from a level above my other components, but no indication occurred that this was an error.  It was through using the tutorial route I had already commented in that helped me realize how the application reads the files.
* Java specificity - being a strongly typed language really requires knowing all the commands and prompts on how to build the code.  All the aspects of the code need to be defined out and called correctly.  It took most of the project time and lots of reading up on the reference material, documentation, emulating, and adjusting code until I felt like I had a better sense/handle of the code base and how it functions.
* Java file management - file structuring and management is essential in Java code, especially given how Java creates class folder structures and the way that code has to call upon itself with the right paths in the directories to properly call on the right classes for things to happen.  It reminds me of how modularity and component building works in ReactJS but with more required terminology to get familiar with to call.

| **Feature Aim** | **Description** | **Feature code requirements** | **Complete?** |
| :--- | :--- | :--- | :--- |
| [Program coded in Java](https://github.com/AshuraKuranata/high-low-java) | Build back-end utilizing Java and Spring as the primary code base | Java, Spring | Yes
| [Front-end/Back-end](https://github.com/AshuraKuranata/spring-psql) | Implement a functional, viewable app using Java/Spring that is accessible on front end | Java, Spring, React/Angular? | Yes
| [Connect to database with CRUD function](https://github.com/AshuraKuranata/spring-psql) | Implement a database with CRUD functionality to Java/Spring based program | MongoDB or SQL | Yes
| [User Authentication](https://github.com/AshuraKuranata/spring-user-auth): [backend here](https://github.com/AshuraKuranata/userauth)  | Implement a secure user authentication program into application | JWT (if using Django/SQL) or OATH2? | Yes
| Professional look | I want to implement a CSS framework (tailwind/bootstrap/other) and use figma models to make the site look professional | Tailwind/Bootstrap, Figma model | No

### Learnings
I'm glad to have done the process and core of the project in Java/Spring, I think it's really helped me fundamentally understand coding at this level of abstraction even more than I had previously.  If I had a choice, for the purposes of ease and time, I see why and how other programming languages are preferred to use compared to Java/Spring for ease of use, but conversely I can also see how Java with how long it has been around and its building over the years on how you can channel some interesting builds through a proper implementation.