# Giter8 Starer Project for Cassandra

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
* Uses the [TypeSafe Config project[https://github.com/typesafehub/config] for cluster configuration. 

## Assumptions
* You have Cassandra running on your local machine (or see see src/test/resources/reference.conf to configure Cassandra).
* Scala version 2.11.2 (for now -- if requested I'll probably add support for other Scala versions)
* You'll need sbt and giter8 of course.

Enjoy, and check out thes other great [giter8 templates](https://github.com/n8han/giter8/wiki/giter8-templates) as well.


