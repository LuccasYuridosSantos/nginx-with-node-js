# nginx-with-node-js

Nesse desafio será utilizado nginx como proxy reverso. A idéia principal é que quando um usuário acesse 
o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um 
registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

O retorno da aplicação node.js para o nginx deverá ser:

`<h1>Full Cycle Rocks!</h1>`

- Lista de nomes cadastrada no banco de dados.

Teremos o docker-compose de uma forma que basta apenas rodarmos: docker-compose up -d que tudo deverá estar funcionando e disponível na porta: 8080.


###Para rodar a aplicação utilize o docker-compose.

```bash
docker-compose up -d
```

###Para acessar, digite o seguinte endereço no navegador:

`http://localhost:8080/`
