# Simple Multiplication Game

This is a simple multiplication game where User can guess the multiplication of given numbers. Focus is on learning and implementation of microservices.

* **Architecture** - Microservices
* **Microservices Design Pattern** - Gateway

Components:
  1. Multiplication Service - Core service for Multiplication Game
  2. Gamification Service - Service that generate the scores, leaderboards and badges
  3. Gateway Service - API Gateway with Load Balancing capabilities
  4. Logs - Centralized logging for all the microservices
  5. Front End 
 
 Technology Stack:
  1. Backend - Java, Frontend - React.js
  2. Spring Boot - Libraries used Web, Cloud, Actuator, Load Balancer, Service Discovery, AMQP, Gateway
  3. Message Broker - RabbitMQ
  4. Service Discovery and Centralized Configuration - Consul
  5. Database - H2 In-memory database
  6. Containerization - Docker, Docker-Compose
