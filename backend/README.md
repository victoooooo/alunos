# Backend - API simulada com JSON-SERVER

## Primeiros passos

* Instale o json-server utilizando o comando abaixo:

```
npm install -g json-server
```

* Para iniciar o servidor/API utilize o seguinte comando (O arquivo db.json deve ser criado manualmente):

```
json-server --watch db.json --port 8080
```

* Utilize um aplicativo para testar a API, pode ser utilizado o Insomnia, Postman ou Restlet Client (extensão do chrome)

# Este projeto simula nossa API/backend para utilização no projeto CRUD de alunos com React, utilize os métodos abaixo para testar seja no Insomnia, Postman ou Restlet Client.

* Para listar todos os alunos utilize o método HTTP GET:

```
http://localhost:8080/alunos
```

* Para listar um aluno pelo id utilize o método HTTP GET:

```
http://localhost:8080/alunos/1
```

* Para incluir um aluno utilize o método HTTP POST com os dados do aluno no body da requisição:

```
http://localhost:8080/alunos
```

* Para atualizar um aluno utilize o método HTTP PUT com os dados do aluno que serão atualizados no body da requisição:

```
http://localhost:8080/alunos/1
```

* Para deletar um aluno passe o id e utilize o método HTTP DELETE:

```
http://localhost:8080/alunos/1
```