# Resilia módulo 3: "Estão servidos?"
###  <p>🎯 Objetivo:</p>
Desenvolver um servidor de teste (json-server) contendo 2 ou mais rotas nas quais o usuário poderá realizar os métodos GET, POST, PUT, DELETE, utilizando algum framework como o insomnia para envio de requisições.
###  Install global : 

    npm install -g json-server
    
###  Execute : 
    npx json-server --watch db.json
    
###  Execute route (para iniciar com as rotas personalizadas) : 
    json-server -r route.json --watch db.json

# ROTAS:

## ENTIDADE SALAS:

| Método | Descrição                     | Rota              |
| ------ | ----------------------------- | ----------------- |
| POST   | CRIAR SALAS                   | `/salas/`         |
| GET    | RETORNAR LISTA DE SALAS       | `/salas/`         |
| PUT    | ATUALIZAR LISTA DE SALAS      | `/salas/:id`      |
| DELETE | DELETAR SALAS                 | `/salas/:id`      |
| ------ | ---------------               | ----------------  |

## ENTIDADE FUNCIONÁRIOS:

| Método | Descrição                      | Rota               |
| ------ | -----------------------------  | ------------------ |
| POST   | CRIAR FUNCIONÁRIOS             | `/funcionarios/`   |
| GET    | RETORNAR LISTA DE FUNCIONÁRIOS | `/funcionarios/`   |
| PUT    | ATUALIZAR LISTA DE FUNCIONÁRIOS| `/funcionarios/:id`|
| DELETE | DELETAR FUNCIONÁRIOS           | `/funcionarios/:id`|
| ------ | ---------------                | ------------------ |


## ENTIDADE CLIENTES:

| Método | Descrição                      | Rota               |
| ------ | -----------------------------  | ------------------ |
| POST   | CRIAR CLIENTES                 | `/clientes/`       |
| GET    | RETORNAR LISTA DE CLIENTES     | `/clientes/`       |
| PUT    | ATUALIZAR LISTA DE CLIENTES    | `/clientes/:id`    |
| DELETE | DELETAR CLIENTES               | `/clientes/:id`    |
| ------ | ---------------                | ------------------ |

### ❔Como utilizar insomnia:
Para realizar nossa primeira requisição, vamos pressionar o botão com um símbolo de mais (+) e então clicar em “New Request”<br>
![insomnia.png](https://www.imagemhost.com.br/images/2023/02/10/insomnia.png)

O painel à nossa direita será aberto. Nele, poderemos informar a URL da nossa API na parte superior, ao lado do método, que neste caso é “GET”. A URL de nossa API para listar os funcionarios é http://localhost:3000/funcionarios
[![imageb6a86a21cfe69c74.png](https://www.imagemhost.com.br/images/2023/02/10/imageb6a86a21cfe69c74.png)](https://www.imagemhost.com.br/image/rI714J)

Após informar o endereço da API, basta clicar em “Send”. Em seguida, o painel mais à direita nos retornará os dados:
![imagea04b39a165ece69f.png](https://www.imagemhost.com.br/images/2023/02/10/imagea04b39a165ece69f.png)

## 🦸‍♂️ Autor

<table>
<tr>
<td>
<b>João Vitor Dias Évora</b>
<br>

[![Linkedin Badge](https://img.shields.io/badge/joaovitorevora-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&link=https://www.linkedin.com/in/joaovitorevora/)](https://www.linkedin.com/in/joaovitorevora/) [![Github Badge](https://img.shields.io/badge/joaovitorevora-100000?style=for-the-badge&logo=github&logoColor=whitee&link=https://github.com/joaovitorevora)](https://github.com/joaovitorevora)

</table>

## 📝 Licença

Projeto Feito por João Vitor Dias para Resilia Educação em parceria com a RD.

---
![Badge Concluído](http://img.shields.io/static/v1?label=STATUS&message=CONCLUÍDO&color=GREEN&style=for-the-badge)
