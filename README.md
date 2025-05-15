# Microservice Solution

A scalable and maintainable microservice architecture design to handle high data volumes following the best API practices.

## Objective
To build a robust and efficient microservice capable of processing large datasets with low latency, scalability, and clean architecture principles.


### Specific Objectives
- Handle data search and manipulation
- Responses must be under 500ms
- Maximun of 10% degradation 
- Horizontaly Auto Scaling

## Solution Modules
- [API](api/api.md)
- [Container](container/container.md)
- [kubernetes](kubernetes/kubernetes.md)
- [Pipelines](pipelines/pipelines.md)
- [Tests](test/test.md)

## Technical Decisions
- Architecture: `Adaptation of Clean Arch`
- Stack: `Typecript`
- Database: `MongoDb`

> The architecture promotes separation of concerns, testability, and high cohesion across layers.


## Roadmap

Planned improvements and scalable integrations for future iterations:

- Caching (e.g. Redis)
- Message Queues (e.g. RabbitMQ)
- Monitoring and Observability (e.g. OpenObserver, Grafana, Zabix)