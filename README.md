# java-web-maven-spring-jsp-cockroachdb-single-node-without-ssl-simple

## Description
A jsp springboot java maven build,
that connects to cockroach database.

A java maven build, that connects to single node
cockroach database without ssl.

## Tech stack
- springboot
  - jsp
- maven
  - postgres drivers
  - lombok
- bootstrap
- jquery
- dataTable

## Docker stack
- cockroachdb/cockroach:v19.2.2
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
