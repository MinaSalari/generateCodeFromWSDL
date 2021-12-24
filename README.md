
# GenerateCodeFromWSDL

This is maven plugin project that generate java code from WSDL by using jaxb2-maven-plugin.
You must add your wsdl into resource file of this project, then replace pom file tag values by your project values.
At the end build this project and your codes are ready!

### Prerequisites

* [Java 1.8](http://www.oracle.com/technetwork/java/javase/downloads/index.html) - Programming language

## Built With

* [Maven](https://maven.apache.org) - Dependency management

## Instruction
###Configuration

<packageName>com.tosan.core.vostro.service.bl.swift</packageName>
* write your poject package name in this tag.

<source>src/main/resources/SwiftCommService.wsdl</source>
* put your wsdl file in this path and then put its name in this tag.

<outputDirectory>target/generated-sources/</outputDirectory>
* generated code will be in this path after build of project.


## Author

* Mina Salari

