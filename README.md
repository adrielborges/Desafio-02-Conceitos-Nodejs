# Conceitos do Node.js

## Desenvolvido para o Desafio Nº 02 do bootcamp GoStack - @Rocketseat

“Não espere para plantar, apenas tenha paciência para colher”
<br/><br/><br/><br/>

### Nesse desafio foi pedido para construir uma api em node.js usando os conceitos passados nas aulas

 O objetivo era uma aplicação de repositórios para portifólio onde podemos dar likes, criar,deletar, listar e atualizar repositórios.

Rotas da aplicação

* POST /repositories: A rota recebe title, url e techs dentro do corpo da requisição, sendo a URL o link para o github desse repositório. Ao cadastrar um novo projeto, ele armazena dentro de um objeto no seguinte formato: { id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...', techs: ["Node.js", "..."], likes: 0 }; Certifique-se que o ID seja um UUID.

* GET /repositories: Rota que lista todos os repositórios;

* PUT /repositories/:id: A rota altera apenas o title, a url e as techs do repositório que possua o id igual ao id presente nos parâmetros da rota;

* DELETE /repositories/:id: A rota deleta o repositório com o id presente nos parâmetros da rota;

* POST /repositories/:id/like: A rota aumenta o número de likes do repositório específico escolhido através do id presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes aumenta em 1;

<img src="https://raw.githubusercontent.com/rocketseat-education/bootcamp-gostack-desafios/master/desafio-conceitos-nodejs/assets/nodejs-example.png"/>

### Todos os testes foram passados com sucesso na aplicação 
<img src="https://github.com/adrielborges/Desafio-02-Conceitos-Nodejs/blob/master/assets/readme-assets/test-conclusion.png?raw=true"/>


