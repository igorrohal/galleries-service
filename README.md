
galleries-service microservice
===========================

Originally created on 2016-10-13.

My new galleries service

To run locally
--------------

This Spring Boot microservice is driven using Maven. To run locally simply execute the following from the command line:

```shell
> ./mvnw spring-boot:run
```

To run tests
------------

This microservice comes with some rudimentary tests as a good starting point for writing your own. Use the following command to execute the tests using Maven:

```shell
> ./mvnw test
```

Extend the project
--------------------

The following Atomist editors are available for this project:

 * Add support for [building Docker images](https://api.atomist.com/v1/projects/editors/2006fbe0-fcbb-4b52-a282-1ac99e296ed1) (incl. Maven configuration and addition of `Dockerfile`)
 * Add support for [Netflix Hystrix](https://api.atomist.com/v1/projects/editors/97357b3d-9269-417f-bc05-133e8c5ac2c9), an implementation of the circuit breaker pattern
 * Update the [listen port of the embedded HTTP server](https://api.atomist.com/v1/projects/editors/9090c8de-be9f-4a99-96b1-ed8890a9f879) (in `application.properties` and `Dockerfile`)



---
Created by Atomist. Need Help? <a href="https://join.atomist.com/">Join our Slack team</a>
