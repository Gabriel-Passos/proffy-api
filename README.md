<h1 align="center" >
  <img height="120px" width="420px" src="https://user-images.githubusercontent.com/43184223/89253591-6e266280-d5f3-11ea-9519-46582c8032d7.png">
</h1>

<p align="center">
  <a href="https://expressjs.com/"><img src="https://img.shields.io/static/v1?label=Express&message=4.17.1&color=blue&style=flat"/><a/>
  <a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/static/v1?label=TypeScript&message=3.7.2&color=blue&style=flat"/></a>
  <a href="http://knexjs.org/"><img src="https://img.shields.io/static/v1?label=Knex&message=0.21.2&color=blue&style=flat"/></a>
</p>
  
> Status do Projeto: Em desenvolvimento. :warning:

### Tópicos 

:small_blue_diamond: [Descrição do projeto](#descrição-do-projeto)

:small_blue_diamond: [Como rodar a aplicação](#como-rodar-a-aplicação-arrow_forward)

:small_blue_diamond: [Tecnologias utilizadas](#tecnologias-utilizadas)

:small_blue_diamond: [Desenvolvedores](#desenvolvedores-octocat)

## Descrição do projeto

### O que é Proffy API?

<p align="justify">
  API RESTFul desenvolvida em NodeJS com a finalidade de realizar cadastros e fornecer os dados necessários para o Front-end.
</p>

## Como rodar a API :arrow_forward:

Acesse o terminal, e clone o projeto com o seguinte comando: 

```
git clone https://github.com/Gabriel-Passos/proffy-api.git
```

### Back-end

- Para rodar a api, precisamos instalar as dependências do projeto, portanto entre na pasta backend e execute o seguinte comando:

```
yarn 

ou 

npm install
```

- A pasta `node_modules` irá aparecer depois da instalação das dependências.

- Agora falta pouco para rodar a api, ainda com o terminal aberto na pasta backend execute: 

```
yarn dev:server

ou

npm run dev:server
```

Você encontrará a API rodando em: http://localhost:3333

A seguinte mensagem irá aparecer:

```
Cannot GET /
```
#### Portanto com a API rodando, teste os seguintes endpoints: [/classes](http://localhost:3333/classes) e [/connections](http://localhost:3333/connections)

## Tecnologias utilizadas

- [NodeJS](https://nodejs.org/en/docs/)
- [Express](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/docs/home.html)
- [Knex](http://knexjs.org/)

## Desenvolvedores :octocat:

[<img src="https://avatars3.githubusercontent.com/u/43184223?s=460&u=50810abc34900ea6134a9bd0b8a04e2c8640ddc4&v=4" width=115><br><sub>Gabriel Passos</sub>](https://github.com/Gabriel-Passos)
