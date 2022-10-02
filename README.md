# java-cli-gradle-postgresql-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

A java gradle build, that connects to postgresql database.

## Tech stack
- java
- gradle
  - log4j
  - postgresql drivers

## Docker stack
- postgresql:alpine
- gradle:jdk11

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
