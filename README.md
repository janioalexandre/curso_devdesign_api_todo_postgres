# API REST NodeJS - APP Todo com Express e Postgres (SQL) - deploy no Heroku

API todo

Listar usuários no browser 
https://api-node-todo-postgres-janio.herokuapp.com/users

# Teste da API utilizando a ferramenta Insomnia

Logar:
https://api-node-todo-postgres-janio.herokuapp.com/session
POST
JSON:
{
	"username" : "janioalexandre@gmail.com"
}

Criar todo
https://api-node-todo-postgres-janio.herokuapp.com/todo/1
POST
JSON:
{
	"description": "Construir API node com postgres",
	"done": false
}

Listar todos
https://api-node-todo-postgres-janio.herokuapp.com/todo/1
GET passando o user_id

Atualizar todo 
https://api-node-todo-postgres-janio.herokuapp.com/todo/2/5
PATCH passando user_id e todo_id
JSON:
{
	"description": "Construir API node com postgres",
	"done": true
}

Deletar todo
https://api-node-todo-postgres-janio.herokuapp.com/todo/1/1
DELETE passando user_id e todo_id



#
Curso ministrado pelo Dev & Design