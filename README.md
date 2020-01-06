# Alura cursos online - Fundamentos Django 2 (Parte 3): Uma aplicação web

Projeto da Alura cursos online, desenvolvido em Python3 com framework Django

## Projeto final aula 2

Nessa aula:

- Tentamos recuperar os dados do formulário através do verbo HTTP `POST`, porém recebemos uma mensagem informando que o token de segurança não foi encontrado;

- Para solucionar, adicionamos a template tag `{% csrf_token %}` e  recuperamos o nome enviado na requisição através do código `request.POST['nome'];

- Criamos algumas validações e criamos um novo usuário em nossa aplicação.
