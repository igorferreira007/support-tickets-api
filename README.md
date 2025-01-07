# Support Tickets API

Essa aplicação tem como proposito criar, editar, atualizar, pesquisar ou remover tickets de suporte. Ela foi a primeira API do curso Full-Stack da Rocketseat, feita apenas com Node.js sem uso de frameworks. Os dados para testes da api foram salvos no arquivo db.json, que é gerado ao iniciar o servidor.

## Tecnologias

- Node.js

## Principais rotas

- **Create (POST)**: http://localhost:3333/tickets  
  Exemplo do corpo da requisição:  
  {
  	"equipment": "Teclado",
  	"description": "Não funciona",
  	"user_name": "Igor Ferreira"
  }
  
- **Index (GET)**: http://localhost:3333/tickets

- **Index with Filters (GET)**: http://localhost:3333/tickets?status=closed ou http://localhost:3333/tickets?status=open
  
- **Update (PUT)**: /tickets/:id  
  Exemplo do corpo da requisição:  
  {
  	"equipment": "Teclado",
  	"description": "Teclado não funciona o espaço",
  	"user_name": "Igor Ferreira"
  }
  
- **Close (PATCH)**: http://localhost:3333/tickets/:id/close  
  Exemplo do corpo da requisição:  
  {
  	"solution": "Teclado substituido"
  }
  
- **Remove (DELETE)**: http://localhost:3333/tickets/:id

## Como executar

1. Clone o repositório:  
   ```
   git clone https://github.com/igorferreira007/support-tickets-api.git

2. Navegue para o diretório do projeto.

3. Inicie o servidor:
    ```
    npm run dev

4. Utilize alguma ferramenta para teste de APIs passando os endpoints.
