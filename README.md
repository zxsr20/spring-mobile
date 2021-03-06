# Spring Mobile

[Spring Mobile](http://www.springsource.org/spring-mobile) is an extension to [Spring MVC](http://static.springsource.org/spring/docs/current/spring-framework-reference/html/mvc.html) that aims to simplify the development of mobile web applications.

## Check Out and Build from Source

1. Clone the repository from GitHub:

		$ git clone git://github.com/SpringSource/spring-mobile.git

2. Navigate into the cloned repository directory:

		$ cd spring-mobile

3. The project uses [Gradle](http://gradle.org/) to build:

		$ ./gradlew build

## Eclipse

To generate Eclipse metadata (.classpath and .project files), use the following Gradle task:

	$ ./gradlew eclipse

Once complete, you may then import the projects into Eclipse as usual:

	File -> Import -> Existing projects into workspace

Alternatively, [SpringSource Tool Suite](http://www.springsource.com/developer/sts) has built in support for [Gradle](http://gradle.org/), and you can simply import as Gradle projects.

## IDEA

To generate IDEA metadata (.iml and .ipr files), use the following Gradle task:

	$ ./gradlew idea

## JavaDoc

Use the following Gradle task to build the JavaDoc

	$ ./gradlew :docs:api

_Note: The result will be available in 'docs/build/api'._
