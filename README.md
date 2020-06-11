Desafio Fundamentos NodeJS
Criar uma aplicacao NodeJS junto ao TypeScript
Utilizando os conceitos de models, repositories e services

Armazenar transações financeiras, entrada e saída, permitir o cadastro e a listagem das transações

Os conceitos de models, repositories e services

Os models, entidade ou modelos define o formato de um dado que é armazenado em algum array, variavel ou banco de dados

Os repositories são uma conexao entre a persistencia dos dados, e a nossa rota dentro de repositorios vamos buscar informacoes dentro de um banco ou variavel.
Sempre que for armazenar qualquer tipo de dado, o repositorio sera usado para conseguir realizar operacoes em cima desses dados(criar, ler, editar, deletar...)

Os services um dos grandes motivos pra criar services e tirar regra de negocio da rota para nao ferir os principios de nao repitir regra de negocio dentro da aplicacao

Separando as parte da aplicacao em models, repositories e service. Respeitamos o principio de responsabilidade unica refarotando e organizando o nosso codigo nossa aplicacao

![c](https://user-images.githubusercontent.com/45858897/84346694-f0ac1c00-ab86-11ea-8a5b-14843843b1fc.gif)
