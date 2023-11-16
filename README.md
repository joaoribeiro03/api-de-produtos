# API de Produtos

Essa é uma API de Produtos desenvolvida em Java usando o Spring Boot. Essa aplicação permite a inserção, listagem, atualização e exclusão de produtos.

## Funcionalidades

- **Cadastro de Produto**: Permite o registro de produtos com seus nomes e valores.

## Principais Tecnologias Utilizadas

- **Java**
- **Spring Boot**
- **Maven**
- **Postman**
- **MySQL**

## Endpoints

- `POST /products`: Cria um novo registro de produto com nome e valores.
- `GET /products`: Retorna todos os produtos cadastrados.
- `GET /products/{id}`: Retorna um produto específico com base no ID.
- `PUT /products/{id}`: Atualiza os dados de um produto específico com base no ID.
- `DELETE /products/{id}`: Exclui um produto com base no ID.

## Configuração

Para utilizar a API, siga as etapas:

1. **Requisitos**:
   - Java Development Kit (JDK)
   - Maven
   - MySQL
   - Postman
   - IDE (Utilizei o Eclipse)

2. **Clonar o Repositório.**

3. **Configuração do Banco de Dados**:
- Crie um banco de dados no MySQL.
- Configure as credenciais do banco de dados no arquivo `application.properties`.

4. **Execução**:
- Navegue até a pasta do projeto.
- Execute o comando: mvn spring-boot:run