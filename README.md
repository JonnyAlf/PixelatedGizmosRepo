Spring Boot CRUD de Produtos

Este projeto é uma aplicação simples que demonstra operações CRUD (Create, Read, Update, Delete) para gerenciar produtos utilizando Spring Boot.

Tecnologias Utilizadas
Java 17
Spring Boot
Spring Data JPA
HATEOAS
PostgreSQL

Configuração

Certifique-se de ter o JDK 17 e o PostgreSQL instalados em sua máquina.

Passos para execução:

Clone este repositório:
bash
git clone https://github.com/seu-usuario/spring-boot-crud-produtos.git

Abra o projeto em sua IDE.

Certifique-se de configurar corretamente o banco de dados PostgreSQL no arquivo application.properties.

Execute a aplicação a partir da classe principal SpringbootApplication.

Endpoints Disponíveis

POST /products

Cria um novo produto.

GET /products

Recupera a lista de todos os produtos.

GET /products/{id}

Recupera um produto específico pelo seu ID.

PUT /products/{id}

Atualiza um produto existente.

DELETE /products/{id}

Exclui um produto pelo seu ID.
