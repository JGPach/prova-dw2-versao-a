# Respostas — Prova Prática Individual de DW2 — Versão A

Nome:
RA:

## R1 (Item 10)

Status da página `/`: 302

Status da API `/api/palestrantes`: 401

Explicação:

Quando tentei acessar a página sem estar logado, o sistema me redirecionou para a tela de login. Já na API, apareceu o erro 401, informando que é necessário estar autenticado para acessar os dados. Isso acontece porque a página faz um redirecionamento, enquanto a API retorna uma mensagem de erro em JSON.

## R2 (Item 11)

Status observado: 405 (Method Not Allowed).

Explicação:

Ao executar o comando POST na rota `/api/palestrantes`, o servidor retornou o erro 405 porque essa rota aceita apenas requisições GET. Ou seja, não é permitido enviar dados usando o método POST nesse endereço.