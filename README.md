# Spring Boot with kafka and docker

## Learn how to integrate Spring Boot with Docker image of Kafka Streaming Platform.

Spring Boot provides ready made templates to implement Kafka Producer and Kafka Consumer applications that write and read data to and from Kafka topics.

In this example we run the Kafka on Docker Container and try to invoke the producer with Spring REST API and write data to kafka topic and once the data or message arrived on kafka topic Kafka consumer will read the message by deserializing it from kafka topic and prints the message on console.

Spring provides kafka listener template to consume the messages from kafka topics in easy way.

## Run the application stack
We have docker-compose.yml file,Start up the application stack using the docker-compose up command. We’ll add the -d flag to run everything in the background.
```bash
docker-compose up -d
```

Stop docker
```bash
docker-compose down
```