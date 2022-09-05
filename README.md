# ToDo API 2

API feita para cumprir segundo desafio da trilha de Node.js do curso Ignite da Rocketseat e tem como objetivo por em prática o que foi aprendido. Nesse desafio busco ir mais a fundo com middlewares no Express.
(Obs: é uma "continuação"/"segunda versão" do repositório: https://github.com/edutdutra/to-do-api).

Essa é uma aplicação para gerenciar tarefas (ou *todos*) mas com algumas mudanças. É permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Tudo isso para cada usuário em específico. Além disso, nessa versão 2 temos um plano grátis onde o usuário só pode criar até dez *todos* e um plano Pro que irá permitir criar *todos* ilimitados, isso tudo usando middlewares para fazer as validações necessárias.
