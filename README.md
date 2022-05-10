# spring-boot-microservices


The architecture consists / will consist of following services:
* counterservice
* configservice
* servicediscovery
* adminservice
* gatewayservice

## How to run

```
git clone https://github.com/eiselems/spring-boot-microservices.git && cd spring-boot-microservices
mvn clean package -DskipTests && docker-compose up --build
```

Access http://localhost:9999/api/cs/count and refresh a few times to see the counter increase.
You also can access the counterservice itself directly at http://localhost:8080/count.