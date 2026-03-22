# Primeira Entrega: API de Produtos (CRUD)

Repositório destinado ao primeiro checkpoint prático da disciplina de **Desenvolvimento de Sistemas Web** (curso de TIC - UFSC Araranguá), ministrada pelo Prof. Matheus Cataneo.

## Sobre o Projeto

Esta API foi desenvolvida como uma introdução prática ao ecossistema .NET. O sistema consiste em um CRUD básico focado no gerenciamento de produtos, aplicando na prática conceitos fundamentais vistos em aula, como:

- Construção de APIs RESTful utilizando **.NET 8**.
- Conexão e manipulação de banco de dados relacional com **PostgreSQL**.
- Mapeamento objeto-relacional (ORM) através do **Entity Framework Core**.
- Documentação e teste de rotas com **Swagger**.

Este código representa a estrutura inicial e servirá de base para a evolução do projeto final da matéria.

## Tecnologias e Ferramentas
- C# / .NET 8 SDK
- PostgreSQL & pgAdmin 4
- Entity Framework Core 8
- Swagger OpenAPI

## Endpoints da API

O projeto possui as seguintes rotas configuradas para a manipulação da entidade `Produto`:

- `GET /api/produtos` ➔ Lista todos os produtos cadastrados no banco.
- `GET /api/produtos/{id}` ➔ Retorna os detalhes de um produto específico.
- `POST /api/produtos` ➔ Adiciona um novo produto.
- `PUT /api/produtos/{id}` ➔ Atualiza as informações de um produto já existente.
- `DELETE /api/produtos/{id}` ➔ Deleta um registro permanentemente.
