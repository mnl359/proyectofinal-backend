# Proyecto final: Aplicación de pizzas

Aplicación de pizzas usando Spring Boot y desplegada en AWS

## Arquitectura

![](images/backend-infra.png)

Para el backend de la aplicación, la infraestructura necesaria es:

* Internet gateway.
* Application load balancer.
* Amazon Elastic Container Service with EC2 instances.
* Amazon RDS for MYSQL.

## Requisitos de software

Para correr esta aplicación sin CI/CD, es necesario tener:

- Maven
- Java
- terraform

Si se quiere usar el pipeline diseñado para esta aplicación se necesita una cuenta en CircleCI.
