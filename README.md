# Desafio Nginx com Node.js

Desafio para colocar em prática a utilização do nginx como proxy reverso. 
A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em um banco de dados mysql, cadastrando um nome na tabela people.

O retorno da aplicação node.js para o nginx deverá ser:

<h1>Full Cycle Rocks!</h1>

- Lista de nomes cadastrados no banco de dados.

* Para executar: 
docker-compose up -d
porta: 8080

* A linguagem de programação para este desafio é Node/JavaScript.