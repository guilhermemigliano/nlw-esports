# 🚀 NextLevelWeek e-Sports

## Introdução

Evento realizado pela 🚀 [Rocketseat](https://www.rocketseat.com.br) entre os dias 13 de setembro de 2022 e 16 de setembro de 2022.

Durante o evento foi desenvolvido um sistema que permite ao usuário cadastrar um anúncio na plataforma para encontrar jogadores interessados em jogar junto.

## Aplicação

O desenvolvimento foi separado em 3 partes, são elas:

- Front-end: Desenvolvido utilizando ReactJS
- Back-end: Desenvolvido utilizando NodeJS
- Mobile: Desenvolvido utilizando React Native

### Screenshots

#### Aplicação web

|                                                Web 1                                                 |                                                Web 2                                                 |
| :--------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: |
| ![Web-1](https://github.com/guilhermemigliano/nlw-esports/blob/main/screenshots/web-01.png?raw=true) | ![Web-2](https://github.com/guilhermemigliano/nlw-esports/blob/main/screenshots/web-02.png?raw=true) |

#### Aplicação mobile

|                                                  Mobile 1                                                  |                                                 Mobile 2                                                  |                                                 Mobile 3                                                 |
| :--------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------: |
| ![Mobile-1](https://github.com/guilhermemigliano/nlw-esports/blob/main/screenshots/mobile-1.png?raw=truee) | ![Mobile-2](https://github.com/guilhermemigliano/nlw-esports/blob/main/screenshots/mobile-2.png?raw=true) | ![Mobile-3](https://github.com/guilhermemigliano/nlw-esports/blob/main/screenshots/mobile3.png?raw=true) |

### Web

A aplicação web trata-se de um sistema em que o usuário pode inserir um anúncio e verificar outros anúncios de uma lista de jogos.

#### Tecnologias e Bibliotecas

- [ViteJS](https://vitejs.dev/guide/) - Utilizado para criar um ambiente de desenvimento React utilizando a linguagem TypeScript;
- [TailwindCSS](https://tailwindcss.com) - Framework utilizado na estilização (css) do sistema;
- [PhosphorIcons](https://phosphoricons.com) - Biblioteca de ícones utilizados na aplicação;
- [HeadlessUI](https://headlessui.dev) - Componentes prontos focados na acessibilidade do usuário;
- [Axios](https://axios-http.com/ptbr/docs/intro) - Cliente HTTP para node.js e pra o navegador.

### Mobile

A aplicação mobile trata-se da mesma aplicação desenvolvida para web utilizando o React Native para seu desenvolvimento.

#### Tecnologias e Bibliotecas

- [ReactNative](https://reactnative.dev) - Tecnologia utilizada para desenvolvimento do aplicativo;
- [Expo](https://reactnative.dev) - Ferramenta para desenvolvimento mobile com React Native. Facilita no desenvolvimento por possuir diversas bibliotecas prontas de forma nativa para uso.

### Server (backend)

Desenvolvimento da aplicação responsável por receber as informações do usuários (web e mobile), inserir em um banco de dados e fornecer os dados para amostragem na aplicação.

#### Tecnologias e Linguagem de Programação

- [NodeJS](https://nodejs.org/en/) - Utilizado para criar o servidor utilizado na aplicação;
- TypeScript - Linguagem utilizada para criação da aplicação.

#### Dependências

- TS-Node - Utilizado para executar o TypeScript no NodeJS;
- Express - Framework utilizado para criar as rotas de comunicações entre o frontend e o backend;
- Prisma ORM - Utilizado para criar o banco de dados no sistema;
- SQLite - banco de dados utilizado na aplicação.
