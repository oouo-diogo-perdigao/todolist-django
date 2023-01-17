# Trabalho tarefa 11 - Todo ListDjandgo

Olá Alunos,

Uma startup está construindo um produto chamado TodoIt que permite os usuários controlarem as suas tarefas diárias. Para registrar, o usuário fornece o e-mail e a senha. Para cada tarefa, o título, a descrição, a categoria e a data de vencimento.

A tarefa dos pares de programadores da startup é construir o TodoIt, utilizando o Django framework, com as seguintes funcionalidades:

* A criação de um site de administração de tarefas, com o usuário "todoitadmin" e senha "todoitadmin".
* A criação de telas para executar tarefas de manutenção (consulta, inclusão, edição e remoção).
* A criação de uma API para consulta das tarefas pendentes.

Após isso, a equipe deverá criar uma tag chamada tarefa-11 e atualizar todo o conteúdo do repositório remoto. Por fim, envie o link deste repositório pelo Canvas até a data de entrega.

# Instruções para rodar (Power Shell 7):
py -3 -m venv .venv
.venv/Scripts/activate
pip install -r requirements.txt

django-admin startapp todo_app



