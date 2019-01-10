# crispy-rabbit
RabbitMq cluster simulation and load testing setup with docker

## Goals
1. The goal of this project is to get a functional RabbitMQ cluster running across a set of Docker Containers that will support running messaging and high availability simulations.

2. To test failure conditions and how RabbitMq deals with each failure scenario

## Set up 
 
 1. 3-node reference architecture for RabbitMQ clustering without a load balancer. Each RabbitMQ broker runs on a host docker node
