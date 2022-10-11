# java-cli-mill-postgresql-data-type-array

## Description
Creates a small table `dog` that uses
a text array data type. Arrays can also be
numeric.

A java millbuild build, that connects to postgresql database.

## Tech stack
- java
- millbuild
  - log4j
  - postgresql drivers

## Docker stack
- postgresql:alpine
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
