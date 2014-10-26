# Giter8 Starter Project for Cassandra

This is a [giter8](https://github.com/n8han/giter8) template for a simple Cassandra project using Scala.

## Usage
```
g8 codesolid/cassandra
cd <the_directory_created>
sbt test
```

## Features
* Uses the [DataStax Cassandra Driver](http://www.datastax.com/documentation/developer/java-driver/2.0/java-driver/whatsNew2.html)
* Sets up a test connection and tests some basic database operations in [ScalaTest](http://www.scalatest.org/) project.
* Uses the [TypeSafe Config](https://github.com/typesafehub/config) library for cluster configuration. 

## Assumptions
* You have Cassandra running on your local machine (or see see src/test/resources/reference.conf to configure Cassandra).
* I've tested this on Scala 2.10.4 and 2.11.2.  It was designed to run on 2.11, the fact that it worked on 2.10 surprised me,
but don't look a gift horse in the mouth, etc.
* You'll need sbt and giter8 of course.

Enjoy, and check out thes other great [giter8 templates](https://github.com/n8han/giter8/wiki/giter8-templates) as well.


