# shareprice-service
Docker  Compose File for starting all the services

To start services defined in one of the Docker Compose files:

```shell
      docker-compose -f <filename> up [-d]
```

## Docker Compose File Skelton.yml
This starts all the basic services:
1. RabbitMQ
2. Hazelcast Caching
3. Kafka cluster using KRaft

## Docker Compose File Kafka.yml
This starts only Kafka cluster using Kraft.
The Cluster ID is set in each Kafka configuration.