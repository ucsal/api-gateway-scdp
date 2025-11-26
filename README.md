# API Gateway - SCDP

O **API Gateway** atua como a porta de entrada única para todo o ecossistema de microserviços. Ele roteia as chamadas externas para os serviços internos apropriados, utilizando o Service Discovery (Eureka) para localizar as instâncias.

#🚀 Tecnologias

* **Java 17**
* **Spring Boot 3.2.3**
* **Spring Cloud Gateway**
* **Spring Cloud Netflix Eureka Client**

#⚙️ Pré-requisitos

1.  **Discovery Server (Porta 8761)** deve estar rodando.
2.  Java 17 e Maven instalados.

## 🏃‍♂️ Como Rodar

### Via Terminal
```bash
cd api-gateway-scdp
mvn spring-boot:run
