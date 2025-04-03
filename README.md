# Checkpoint 1 - Microservice and Web Engineering (Spring Boot API) 

Projeto desenvolvido como parte de um checkpoint para a disciplina de Microservice and Web Engineering. A aplicação consiste em uma API REST para o controle de registros de uma clínica estética, com a permissão de cadastro e consultas pelos profissionais e pacientes.

## Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Lombok

##  Estrutura do Projeto

A aplicação está organizada nos seguintes pacotes:

- `model`: Contém as classes de entidade (`Paciente`).
- `service`: Camada de regra de negócio.
- `controller`: Responsável por expor os endpoints da API.
- `dto`: Objetos de transferência de dados para as requisições e respostas.


##  Funcionalidades Implementadas

### Paciente

- **GET `/pacientes`**: Retorna todos os pacientes cadastrados.
- **GET `/pacientes/{id}`**: Retorna um paciente por ID.
- **POST `/pacientes`**: Cadastra um novo paciente.
- **PUT `/pacientes/{id}`**: Atualiza os dados de um paciente.
- **DELETE `/pacientes/{id}`**: Remove um paciente do sistema.

## Documentação da API

Acessar:
http://localhost:8080/swagger-ui/index.html


## Rodar o programa

Execute no cmd:
git clone https://github.com/Seergin/checkpointSpringBootAPI.git
