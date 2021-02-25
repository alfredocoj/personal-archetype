# PERSONAL DEMO

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

## WEBSPHERE
### Commands to build

```
docker build -t openliberty-app -f DockerfileLiberty .
```

### Commands to run
```
docker-compose up --build oracle-db mq-ibm
docker-compose up --build websphere
```

## WILDFLY
### Commands to build and run
```
docker-compose up oracle-db activemq
docker-compose up wildfly
```
## CONSOLES

### IBM MQ

```
https://localhost:9443/ibmmq/console
```

## URLs

### WS
```
http://localhost:9080/ws/v1/banks
```

### MQ

```
http://localhost:9080/mq/v1/send
http://localhost:9080/mq/v1/recv
```