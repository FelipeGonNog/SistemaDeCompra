# Sistema de Compras API

API REST desenvolvida em **Java com Spring Boot** para gerenciamento de compras, usuários e produtos, implementando autenticação e controle de acesso utilizando **Spring Security**.

O projeto foi desenvolvido com foco em **boas práticas de engenharia de software**, organização em camadas e integração com banco de dados relacional.

## Tecnologias Utilizadas

- Java
- Spring Boot
- Spring Security
- JPA / Hibernate
- SQL
- Maven
- REST APIs
- Git

## Arquitetura

O projeto segue uma arquitetura em camadas:

Controller  
Responsável pela exposição dos endpoints REST.

Service  
Contém a lógica de negócio da aplicação.

Repository  
Responsável pela comunicação com o banco de dados.

Model  
Representação das entidades do sistema.

Essa separação facilita manutenção, escalabilidade e organização do código.

## Funcionalidades

- Cadastro de usuários
- Autenticação e autorização com Spring Security
- Cadastro de produtos
- Registro de compras
- Consulta de compras realizadas
- Integração com banco de dados relacional

## Segurança

O sistema utiliza **Spring Security** para:

- autenticação de usuários
- controle de acesso
- proteção de endpoints

## Estrutura do Projeto
src
├── controller
├── service
├── repository
├── model
└── config


## Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de praticar:

- desenvolvimento de **APIs REST**
- arquitetura de software em camadas
- autenticação e segurança em aplicações backend
- integração com banco de dados

## Autor

Felipe Gonçalves  
Estudante de Engenharia de Software
