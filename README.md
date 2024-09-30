# Animal API - Projeto Fake API com JSON Server

Este projeto é uma API fake desenvolvida com o **JSON Server**, simulando um serviço de gerenciamento de animais. Ele permite realizar operações CRUD (Create, Read, Update, Delete) para gerenciar dados de animais de forma simples e rápida, ideal para prototipação e testes de front-end. A API consome dados de um arquivo `db.json`, que serve como um banco de dados local.

## Tecnologias utilizadas:
- **JSON Server**: Para simular uma API REST completa.
- **Axios**: Para realizar requisições HTTP de forma assíncrona.
- **JavaScript**: Para o desenvolvimento do cliente de consumo da API.

## Funcionalidades:
- Simulação de uma API REST com endpoints customizados.
- Listagem, criação, atualização e exclusão de dados de animais.
- Testes de consumo de API via Axios, com suporte para requisições assíncronas.
1- ## Instale as dependências do projeto:

npm install

## Como executar:
2. Instale as dependências do projeto:
   ```bash
   npm install



2- Suba o servidor JSON Fake:
npx json-server --host 0.0.0.0 db.json
