[![CI/CD Pipeline](https://github.com/JuanLema14/lab2-cicd-faker/actions/workflows/build.yml/badge.svg)](https://github.com/JuanLema14/lab2-cicd-faker/actions/workflows/build.yml) 
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=JuanLema14_lab2-cicd-faker&metric=alert_status&token=dfd9de4bb910358c5f750e5b300fad44f6a798a4)](https://sonarcloud.io/summary/new_code?id=JuanLema14_lab2-cicd-faker)

# virtualfake

Implementation of a Simple App with the next operations:

Methods:
* Get random nations
* Get random currencies
* Get random Aircraft
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

```shell
$ mvnw spring-boot:run
```
to download the node dependencies

### How to test it

Execute:

```shell
$ mvnw clean install
```

### How to get coverage test

Execute:

```shell
$ mvwn -B package -DskipTests --file pom.xml
```
