 # Bill of Material (BOM) 

 It is a modular, enterprise-grade distribution that delivers a curated set of dependencies.
 
 Basé sur https://repo1.maven.org/maven2/org/springframework/boot/spring-boot-dependencies/
 
## Features 

* Production-ready features provided out of the box
* Curated and harmonized dependencies that just work together
* Modular platform that allows developers to deploy only the parts they need
* Support for embedded runtimes, classic application server, and PaaS deployments
* Depends only on Java SE, and supports some Java EE
* Works with existing dependency management tools such as Maven and Gradle
* This BOM is certified to work on JDK 8 


## Maven howto 

### Prerequisites

#### Minimum version

* Maven >= 3.6.1 https://maven.apache.org/
* Java 1.8

### POM

To use it in your Maven build add:


```xml
  <parent>
    <groupId>fr.ans</groupId>
    <artifactId>bom-ms</artifactId>
    <version>3.0.7</version>
    <relativePath></relativePath>
  </parent>
```
