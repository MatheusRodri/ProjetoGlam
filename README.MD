#  STUDIO EVELYN - PI4

> O projeto **Glam** é um projeto de agendamento online de studio de beleza, onde o cliente pode agendar um horário para fazer um procedimento no studio de beleza e efetuar o pagamento online. O(A) dono(a) do studio de beleza pode ver os agendamentos e confirmar o agendamento.

## Sumário

- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Rodar](#como-rodar)
  - [Pré-requisitos](#pré-requisitos)
- [Como Usar](#como-usar)
- [Como Contribuir](#como-contribuir)


## Funcionalidades

- Cadastro de clientes
- Login de clientes
- Agendamento de procedimentos
- Pagamento online com Stripe
- Gestão de agendamentos para o dono do studio

## Tecnologias Utilizadas

- Banco de Dados:
  - MySQL
- Backend:
  - JavaScript
  - Node.js
    - Express.js
    - Sequelize
    - Nodemon
- Frontend:
  - React
    - Axios
    - React Router DOM
    - Styled Components

## Como Rodar
### Pré-requisitos

Antes de executar o projeto, certifique-se de ter os seguintes requisitos instalados:
- Requisitos 1
- Requisitos 2

## Como rodar

- Faça o clone ou download do projeto
- Backend
  - Entre na pasta backend
    - No terminal execute o comando `npm i` para instalar as bibliotecas na qual o projeto precisa.
    - Abra uma nova conexão ou sua existem no MySQL Workbench
    - Copie o texto que está localizado dentro do arquivo **Glam.sql**
    - Cole na conexão aberta e rode
    - Abra o arquivo **.env** e coloque as informações do seu banco de dados e stripe
    - Volte no terminal
    - Execute o comando `npm start` para rodar o projeto backend
- Frontend

  - Entre na pasta frontend
  - No terminal execute o comando `npm i` para instalar as bibliotecas na qual o projeto precisa.
  - Execute o comando `npm start` para rodar o projeto frontend

## Como Contribuir

- Entre em contato comigo pelo [LinkedIn](https://www.linkedin.com/in/matheus-rodrigues-mrj/)