# Microservice-using-Kafka



This repository shows basic Microservice-using-Kafka architecture using kafka, focuses on how Producer service and consumer service communicate using kafka 

-------------------------------run kafka in docker--------------------------
step 1: docker-compose.yml from the solution folder
step 2: docker-compose up -d

-------------------------------run RabbitMQ in docker--------------------------
docker run -d --hostname my-rabbit --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management

