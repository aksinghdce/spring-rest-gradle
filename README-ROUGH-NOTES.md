# spring-rest-gradle
Getting started code for spring rest service with build.gradle

In order to conveniently get started with spring boot:

1. Install spring boot cli binary
2. Install maven binary
3. I gradle binary
4. Install Spring Tool Suite (STS)
5. Start with a getting started project n spring boot from file->new menu
6. You can choose to use command line:
  In this case you have 2 more choices:
    1. Maven: create a pom.xml file. Run "mvn compile", "maven package"
    2. Gradel: create build.gradle file. Run "gradle build", "gradle wrapper", "./gradlew build", edit build.gradle to 
    add application rule and the default main class, "./gradlew run"
    
gradle buildship is preferred over gradle sts which in turn is preferred over maven. Why?
Because maven is incompetent in providing directed acyclic graph type of dependency hierarchy. What that means is that
one build step has to have a predecessor and not more than one predecessor. There are some tricks to configure this
nature to your build project but its not as good as the way gradle does it.
Gradle is more like json and maven is xml! xml is bad as compared to json!! I said it!

The developer needs to understand the concept of dependency injection and why its a valuable concept
Also, the developer needs to have an idea about aspect oriented programming, how and why to use templates 
(to avoid boilerplate code).

The spring boot module simplifies application development with spring by choosing "convention" over "choice". spring boot 
does a lot of default conventional configurations to your project in order to facilitate enterprise level rapid application
development.
