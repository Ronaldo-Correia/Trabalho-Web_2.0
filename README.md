# 🏥 Sistema Clínica - Trabalho WEB

Este projeto é um sistema web para gerenciamento de uma clínica médica, desenvolvido como parte de um trabalho da disciplina de Desenvolvimento Web.
O sistema permite o cadastro de pacientes e profissionais da saúde, além de agendamento e visualização de consultas.

## 🔧 Tecnologias Utilizadas

* Java 17/21
* Spring Boot
* JTE (Java Template Engine)
* HTML/CSS
* Banco de dados H2/PostgreSQL

## 📝 Funcionalidades

* Cadastro e listagem de pacientes
* Cadastro e listagem de profissionais
* Agendamento e listagem de consultas
* Validações de dados nos formulários
* Exibição de dados organizados em uma interface simples

## 👨‍💻 Como executar o sistema localmente

- 1: Substitua o datasource no arquivo `application.yaml` por:
```
  datasource:
    url: jdbc:h2:mem:testdb
    username: sa
    password:
    driver-class-name: org.h2.Driver
```
- 2: No terminal da sua IDE execute esse comando:
```
mvn clean install spring-boot:run
```
- 3: Acesse o site local
[IFBA Medical Group](http://localhost:8081/login)
