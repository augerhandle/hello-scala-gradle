# hello-scala-gradle

## What is this?

An simple hello-world program in Scala using Gradle as the build tool.

It illustrates the following things:
* ultra simple console app that calls out to some classes and uses external libraries
* how to use `slf4j` logging (based on `logback`)
* example of using typesafe config

## Contents

* `README.md` : this file
* `src/main/scala/net/augerhandle/hello/App.scala` : the source code for the console app 
* `src/main/scala/net/augerhandle/hello/*.scala` : other Scala classes used by the app
* `build.gradle` : the Gradle build file used to build and run this project
* `src/main/resources/logback.xml` : the logging config file 
* `src/main/resources/application.conf` : the typesafe config file 

## Building and Running

This is an Gradle-based Scala project. I'm assuming that you have Gradle installed already on your system.

To build the project, execute this command.

* `gradle build`

To run the console application, execute the following command.

* `gradle run`

As a result of running the application, you should see the _usual_ hello world greeting in the console output,
and you should also see a log file in the top-level directory, as specified in `src/main/resources/logback.xml`.



