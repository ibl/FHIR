FHIR
====

Status
------

Incomplete and experimental. For the live sandbox with ongoing experimentation see (https://github.com/ibl/FHIR-Demo)[https://github.com/ibl/FHIR-Demo].


Getting Started
---------------

Clone this repository, start MongoDB, and run

    mvn package
    java -Dserver.port=8080 -Dspring.data.mongodb.uri=mongodb://localhost:27017/fhir -jar target/FHIR.jar
