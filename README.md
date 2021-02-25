# PERSONAL ARCHETYPE

Maven archetype to create a pre-configured maven project for Spring Boot Application.

Supports:

- REST
- Junit
- Hibernate
- OracleDB
- IBMMQ
- ActiveMQ
- Websphere
- Wildfly

## How to use 
### Windowns
```
mvn clean install
cd ..
mvn archetype:generate -DarchetypeGroupId=com.acoj ^ 
-DarchetypeArtifactId=personal-archetype ^ 
-DarchetypeVersion=1.0-SNAPSHOT ^ 
-DgroupId=com.acoj ^ 
-DartifactId=personal-demo
```

### Linux
```
mvn clean install
cd ..
mvn archetype:generate -DarchetypeGroupId=com.acoj \ 
-DarchetypeArtifactId=personal-archetype \ 
-DarchetypeVersion=1.0-SNAPSHOT \ 
-DgroupId=com.acoj \ 
-DartifactId=personal-demo
```

## License
Licensed under the Apache License, Version 2.0.