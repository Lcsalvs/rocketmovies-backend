# 💻 Sobre o desafio

A ideia agora é criar uma aplicação em Node.js onde o usuário cadastra um filme, preenche com algumas informações (nome, descrição, nota) e cria tags relacionadas a ele.


Explicando cada tabela e seus campos:

### Tabela de usuários (users)
- id
- nome do usuário
- e-mail do usuário
- senha do usuário
- avatar do usuário
- data de criação
- data de edição

### Tabela de anotações de um filme (notes)
- id
- título do filme
- descrição do filme
- nota que o usuário deu para o filme*
- id do usuário
- data de criação
- data de edição

### Tabela de tags (movie_tags)
- id
- id da anotação
- id do usuário
- nome da tag**


