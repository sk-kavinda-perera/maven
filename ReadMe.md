# Maven Repository 
Maven is distributed in several formats. The simplest way to install Maven is to download a ready-made binary distribution archive and follow the installation instructions.

## Maven 

**Why do we need to use Apache maven?** 

Maven is used as a build tool. Which is a famous build tool that has about 70 percent usage compared to Gradle and ant.  Very common in large companies. Most used by large open-source projects. (Spring framework, Spring boot) 

**Advantages of Maven** 

* Quick Project Setup (Maven brings conventions over configuration that reduce setup time using archetype) 
* Projects are modular (Very easy setup) 
* Mature Dependency Management 
* Mature Project Build Lifecycle 
* Robust plugin community. 
* Maven also has become the De Facto Standard. 
* Maven Standard Directory Layout 
* Artifact Naming 
* Artifact Repositories 

**Disadvantages of Maven** 

* Projects are described in, and xml document constrained by an XML Schema 
* Gradle uses a Groovy DSL, which can offer greater build flexibility 

**Java Packaging
* **.jar** - Java ARchive - Zip file containing one or more Java class files.
* **.war** - Web Application aRchive - Zip file containing web application. Includes one or more jar files, Java class files, and web resources.
* **.ear** - Enterprise aRchive - Zip file containing one more more WAR files.
* **Fat JAR (aka Uber JAR)** - Executable Jar containing all dependencies. (Used by Spring Boot)
* **Docker Container** - Docker Image containing runtime environment, JVM, and Java package
