# Spring core

This file tells you about Spring core setup and other informations

## Prerequisites

* Maven
* Apache Tomcat 7.0
* Java version 7 or 8


### Setup instructions
- ```New``` > ```Maven Project```
- Type in ```Artifact ID``` as Name of the project, ```Package``` name and ```Group ID```
> Artifact ID and Package is important
- Delete ```src/test/java``` ([Project name > ```src/test/java```](right click) > ```Delete```)
- Update the ```pom.xml``` file by adding dependencies, plugins and properties to add JAR files
- ```Windows + R``` > ```cmd```
```sh
 C:\Users\[name]\workspace\[project_name]
 mvn clean eclipse:eclipse -Dwtpversion=2.0
 ```
- Project Name > ```Maven``` > ```Update Project``` > ```Force Updates of Snapshots/Releases```
- Create XML files
- Create ```src/main/java```
- Use Spring to create objects using dependency injections and display the result.
