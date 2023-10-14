# todo-list-java-spring

A aplicação consiste no backend de uma lista de tarefas (to-do list), contendo as funcionalidades:

- Criar usuários;
- Criar tarefas para o usuário autenticado;
- Alterar tarefas para o usuário autenticado;
- Listar tarefas do usuário autenticado.

## Tecnologias utilizadas:

- Spring Boot V3.0.11 para a criação do servidor web;
- Lombok para facilitar a criação de getters e setters;
- Bcrypt para encriptação de senha antes de salvar o usuário no banco de dados;
- H2Database para criar um banco de dados em memória;

## Rotas da aplicação:

- POST ``/users`` : Usada para criação dos usuários;
- GET ``/tasks`` : Retorna as tarefas do usuário autenticado;
- POST ``/tasks`` : Usada para criação de tarefas;
- PUT ``/tasks/{id}`` : Altera dados da tarefa passada na rota, através do route param ``id`` da tarefa. A tarefa deve pertencer ao usuário logado.


**Nota: Todos os métodos relacionados à rota /tasks usam autenticação básica, onde deve ser informado o usuário cadastrado em /users.**


## Requisitos:

- Ter uma JDK instalada no computador (para rodar no ambiente local);
- Um REST Client para simular as rotas;


## Endereço da aplicação

https://todolist-wansanello.onrender.com


