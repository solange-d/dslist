# DSList
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/solange-d/dslist/blob/main/LICENSE)

# Sobre o projeto

DSList é uma aplicação backend construído durante o curso **Intensivão Java Spring**, evento organizado pela [DevSuperior]
(https://devsuperior.com "Site da DevSupeior").

A aplicação consiste em uma listagem de jogos, implementada no padrão REST, permitindo o reposicionamento de jogos na lista.

## Modelo conceitual

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/solange-d/dslist/blob/main/LICENSE)

![dslist-model](https://github.com/solange-d/dslist/assets/126983450/01790166-92a1-46bd-8d12-7cc220414d26)

## Tecnologias utilizadas
##Back end
- Java
- Spring
- JPA / Hibernate
- Maven
- Banco de dados: H2

# Como executar o projeto

# Backend
Pré-requisitos: Java 17
```bash
# Clonar repositório
git clone https://github.com/solange-d/dslist.git

# Entrar na pasta do projeto backend
cd backend

# Executar o projeto
./mvnw spring-boot:run
```

# Postman
```bash
# Realizar o download da collection
https://github.com/solange-d/dslist/blame/main/DSList.postman_collection.json
 Download raw file

# Importar a collection no Postman
Import > DSList.postman_collection.json

# Transmitir as requisições
Selecione o serviço desejado, exemplo: GET Games e em seguida envie a requisição através do botão Send.

Obs.: Certifique-se de que o projeto está sendo executado em uma IDE compatível e que a execução ocorre sem erros.

```
# O que aprendi neste projeto
Conceitos e implementação a respeito de:
- Sistemas web e recursos
- Cliente/servidor, HTTP, JSON
- Padrão Rest para API web
- Entidades e ORM
- Padrão camadas
- Controller, service, repository
- Padrão DTO
- Estruturação de projeto Spring Rest
- Alimentar uma aplicação com dados de teste - Database seeding
- Relacionamentos N-N - anotação @ManyToMany
- Classe de associação - anotação @EmbeddedId
- Consultas SQL no Spring Data JPA
- Projections - anotação @Query

# Autora
Solange Duemes

https://www.linkedin.com/in/solange-duemes
