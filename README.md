## maven-aggregator-com.sphenon

# Building Sphenon Components

This project is a [maven aggregator](https://maven.apache.org/pom.html#Aggregation)
that builds all Sphenon Java components. It is designed to work with [maven](https://maven.apache.org/)
and [git slave](http://gitslave.sourceforge.net/).

## Cloning

`gits clone https://github.com/616c/maven-aggregator-com.sphenon.git`

This clones the main project as well as all subprojects (Sphenon components).
Alternatively, you can clone the main project with git and then do
a `gits populate`.

## Building

`mvn install`

This builds all components and installs them to your local maven repository.
