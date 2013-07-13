gradle-junit-spock-testng-mixin
===============================

Gradle example project for executing TestNG(Java, Groovy) + JUnit(Java, Groovy) + Spock(Groovy) test cases at same time.

For Maven3 users, see [msakamoto-sf/maven3-junit-spock-testng-mixin](https://github.com/msakamoto-sf/maven3-junit-spock-testng-mixin)

`gradle -version`:
```
Gradle 1.6
Groovy: 1.8.6
Ant: Apache Ant(TM) version 1.8.4 compiled on May 22 2012
Ivy: 2.2.0
JVM: 1.7.0_25 (Oracle Corporation 23.25-b01)
OS: Windows 7 6.1 amd64
```

Play Guide
----

1. Execute only JUnit(Java, Groovy) + Spock(Groovy) test cases
  * `gradle -b build-junit-and-spock.gradle`
2. Execute only TestNG(Java, Groovy) test cases
  * `gradle -b build-testng-only.gradle`
3. Execute TestNG(Java, Groovy) + JUnit(Java, Groovy) + Spock(Groovy) test cases at same time.
  * `gradle -b build-junit-spock-testng.gradle`

References
----

+ gradle-user - Mixed TestNG and JUnit usage?
  + [http://gradle.1045684.n5.nabble.com/Mixed-TestNG-and-JUnit-usage-td1435877.html](http://gradle.1045684.n5.nabble.com/Mixed-TestNG-and-JUnit-usage-td1435877.html)
+ gradle-user - JUnit and TestNG
  + [http://gradle.1045684.n5.nabble.com/JUnit-and-TestNG-td3074015.html](http://gradle.1045684.n5.nabble.com/JUnit-and-TestNG-td3074015.html)
+ Bootstrapping a Java project with Gradle, TestNG, Mockito and Cobertura for Eclipse and Jenkins - Michael G. Noll
  + [http://www.michael-noll.com/blog/2013/01/25/bootstrapping-a-java-project-with-gradle/](http://www.michael-noll.com/blog/2013/01/25/bootstrapping-a-java-project-with-gradle/)
  + miguno/gradle-testng-mockito-bootstrap
  + [https://github.com/miguno/gradle-testng-mockito-bootstrap](https://github.com/miguno/gradle-testng-mockito-bootstrap)
+ Cookbook - Gradle - Codehaus
  + [http://docs.codehaus.org/display/GRADLE/Cookbook#Cookbook-TestNG](http://docs.codehaus.org/display/GRADLE/Cookbook#Cookbook-TestNG)

Java and Groovy source codes are copied from:

+ msakamoto-sf/maven3-junit-spock-testng-mixin
  + [https://github.com/msakamoto-sf/maven3-junit-spock-testng-mixin](https://github.com/msakamoto-sf/maven3-junit-spock-testng-mixin)

