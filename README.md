T20240201
taimara020810

#  Coin Manager
![](https://github.com/alexsandroferreira/coin-manager-api/workflows/CHANGELOG%20Generator/badge.svg)
[![Release](https://img.shields.io/github/v/release/alexsandroferreira/coin-manager-api?color=lgreen)](https://github.com/alexsandroferreira/coin-manager-api/releases)

O projeto CoinManager-api tem como objetivo simular o controle financeiro, incluindo funcionalidades como métricas de valores e cadastro de contas.

 Além disso, será implementada a integração contínua para automatizar o 
 versionamento de código com a biblioteca Release-it.

## Tabela de Conteúdos

- [Tecnologias](#tecnologias)
- [Instalação e Configuração](#instala%C3%A7%C3%A3o-e-configura%C3%A7%C3%A3o)
  - [Requisitos](#requisitos)
  - [Instalação](#instala%C3%A7%C3%A3o)
- [Licença](#licen%C3%A7a)

## Tecnologias 🛠️

Este projeto foi construído com as seguintes tecnologias:

- [Node.js »](https://nodejs.org)
- [Fastify »](https://fastify.dev/)
- [Typescript »](https://www.typescriptlang.org)
- [Zod »](https://zod.dev/)
- [@fatify-type-provider-zod »](https://github.com/turkerdev/fastify-type-provider-zod)
- [@fatify-sweagger »](https://github.com/fastify/fastify-swagger)
- [@fatify-sweagger-ui »](https://github.com/fastify/fastify-swagger-ui)
- [Eslint »](https://eslint.org/docs/latest/)
- [Eslint »](https://github.com/lydell/eslint-plugin-simple-import-sort)
- [@eslint-plugin-simple-import-sort »](https://github.com/Rocketseat/eslint-config-rocketseat)
- [husky »](https://typicode.github.io/husky/)
- [Commitlint »](https://commitlint.js.org/)
- [release-it »](https://github.com/release-it/release-it)
- [extensão vs code rest client »](https://github.com/Huachao/vscode-restclient)

## Instalação e configuração

### Requisitos

- [Node.js »](https://nodejs.org/en/download) na sua versão LTS
- Adicionar extensão [rest client »](https://github.com/Huachao/vscode-restclient), para realizar os testes de api dentro do projeto.
- Para permitir que o changelog rode automaticamente, verifique as configurações do repositório na aba Settings -> Actions -> General Workflow Permissions e marque a opção de permissões de leitura e escrita (Read and Write Permissions).

### Instalação

1. Clone o projeto: `git clone https://github.com/alexsandroferreira/coin-manager-api`.
2. Instale as dependências e ative husky: `npm install` e `npm prepare`.
3. Para iniciar a aplicação execute `npm run build` e `npm run start`.

## Licença

Projeto sob a licença [MIT »](/LICENSE)
