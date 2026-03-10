# Tasks Flask CRUD API

API REST simples para gerenciamento de tarefas desenvolvida com Flask.  
O projeto implementa operações completas de CRUD (Create, Read, Update e Delete) e testes automatizados com Pytest.

## Tecnologias utilizadas

- Python
- Flask
- Pytest
- Requests

## Funcionalidades

A API permite:

- Criar uma nova tarefa
- Listar todas as tarefas
- Buscar uma tarefa específica
- Atualizar uma tarefa
- Deletar uma tarefa

## Estrutura do projeto


tasks-flask-crud
│
├── app.py
├── models
│ └── task.py
├── tests.py
├── requirements.txt
└── README.md


## Instalação

Clone o repositório:


git clone https://github.com/Laguiosta/tasks-flask-crud.git


Entre na pasta do projeto:


cd tasks-flask-crud


Instale as dependências:


pip install -r requirements.txt


## Executando a aplicação


python app.py


A aplicação irá rodar em:


http://127.0.0.1:5000


## Endpoints da API

### Criar tarefa

POST /tasks


{
"title": "Nova tarefa",
"description": "Descrição da tarefa"
}


### Listar tarefas

GET /tasks

### Buscar tarefa por ID

GET /tasks/{id}

### Atualizar tarefa

PUT /tasks/{id}


{
"title": "Novo título",
"description": "Nova descrição",
"completed": true
}


### Deletar tarefa

DELETE /tasks/{id}

## Testes

Para executar os testes automatizados:


pytest tests.py


## Objetivo do projeto

Este projeto foi desenvolvido para praticar:

- criação de APIs REST
- organização de código com Flask
- testes automatizados
- estrutura de backend em Python
