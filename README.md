# Support Tickets API

Essa aplicação tem como proposito criar, editar, atualizar, pesquisar ou remover tickets de suporte. Ela foi a primeira API do curso Full-Stack da Rocketseat, feita apenas com Node.js sem uso de frameworks. Os dados para testes da api foram salvos no arquivo db.json, que é gerado ao iniciar o servidor.

## Tecnologias

- Node.js

## Principais rotas

- Create (POST): /tickets
  Exemplo do corpo da requisição:
  {
  	"equipment": "Teclado",
  	"description": "Não funciona",
  	"user_name": "Igor Ferreira"
  }
  
- Index (GET): /tickets
- Update (PUT): /tickets/:id
- Close (PATCH): /tickets/:id/close
- Remove (DELETE): /tickets/:id
