# Desafio programação - para vaga Full-stack

Por favor leiam este documento do começo ao fim, com muita atenção.
O intuito deste teste é avaliar seus conhecimentos técnicos.

## Requisitos do projeto Backend

* Você deve utilizar como linguagem de programação, python ou golang;
* Os serviços a serem desenvolvidos, devem ser programados para serem publicados no lambda;
* A base de dados dos usuários deve está no MySQL;
* Os dados requeridos para a base de usuário deverá conter: Nome completo, usuário e senha;
* A sessão do usuário deve ser armazenada no DynamonDB;
* Recomendamos que seja utilizado o serverless framework para orquestrar toda a arquitetura do sistema;
* Para atender as requisições do usuário, você deverá utilizar o API Gateway.

## Requisitos do projeto Frontend

* Você deve utilizar o framework Vue;

## Descrição do projeto

Você deverá criar um projeto de boas-vindas para os usuários já existentes na base.
Para isso você precisará criar dois serviços backend, sendo:
* Um serviço que realize o login do usuário e salva a sessão com os dados no banco DynamonDB.
* Um serviço qe retorne esses dados do usuário logado salvo no DynamonDB.

Também será necessário criar uma tela de login para esse usuário e uma segunda de "bem vindo {usuário}"

# O que será avaliado

* Sua capacidade de criar um serviço lambda;
* Sua capacidade de interagir com uma base de dados SQL e NoSQL;
* Arquitetura dos projetos;
* Boas práticas de desenvolvimento (SOLID, design patterns);
* Tratamento de erro;
* Script de publicação do projeto na AWS;
* Integração com os serviços backend;

# O que não será avaliado

* Boas práticas DevOps;
* Não solicitamos um layout bonito;


# Dicas

* Não estamos solicitando um projeto fronend com uma interface visual impecável, foquese nas funcionalidades;
* Remomendamos a utilização do pluging "serverless-offline" para auxiliá-lo no seu desenvolvimento local. (API Gateway / lambda);
* Não pedimos os fluxo completo de autenticação (registrar, esquecia a senha, etc.). Crie os usuários desejados manualmente ou por algum tipo de migration.
* Estamos querendo avaliar seu conhecimento, sugerimos que escolha as coisas que façam mais sentido para a avaliação. Deixei a cereja do bolo por último.
* Caso tenha terminado tudo e queira colocar log e teste na aplicação, sinta-se a vontade.
