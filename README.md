# Autenticação com JWT

Projeto desenvolvido durante a NLW06 da trilha Node.JS na RocketSeat. Este mini projeto tem como objetivo abordar o uso de Sockets para fazer comunicação entre Cliente e Servidor.

## Projeto desenvolvido usando as seguintes tecnologias

-   Node.JS (14.16.1);
-   TypeScript;
-   Yarn; e
-   ORM.

### Configurações Iniciais

Para instalar o Node.JS acesse o site do [Node](https://nodejs.org/) e escolha o seu Sistema Operacional e siga os passos de instalação.
Para instalar o Yarn entre no terminal e execute o seguinte comando:

```sh
npm install yarn
```

Depois instale as dependências do projeto com o comando abaixo:

```sh
yarn install
```

O projeto usa o banco de dados SqLite, para criá-lo execute o comando abaixo:

```sh
yarn migrations
```

Após a execução do comando, observe na pasta "src/database/" que agora terá um arquivo com o nome database.sqlite

## Executando o projeto

Para executar o projeto acesse o terminal e rode o comando abaixo:

```sh
yarn dev
```

Ao executar o comando acima no terminal, uma mensagem será exibida "Server started on 3000"

> Outros scripts podem ser encontrados no arquivo package.json

## Endpoints
[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=nlw6&uri=https%3A%2F%2Fgithub.com%2Fhugomoraismendes%2Fnlw6%2Fblob%2Fmain%2Fdocs%2Finsomnia_endpoints)
