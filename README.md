# Bem vindo ao desafio DevOps da Engineering do Brasil.

Neste desafio queremos validar seus conhecimentos como DevOps, para tanto temos uma app em Python3, esse app é um CRUD de uma base de livros, esse app usa SQLite e queremos agora usar um banco de dados, além disso queremos que esse app tenha um API Gateway e uma rota seja exposta para consumo. 


Esperamos que ao final você nos gere uma imagem Docker contendo o código dessa app funcional.

0. Faça um fork desse projeto, commit todas suas mudanças em seu projeto e nos envie o link do seu fork, para avaliação.
1. Como falado o app usa SQLite e precisamos incluir uma base de dados, você decide qual será a base usada, o importante é que a applicação funcione.
2. O API Gateway desse desafio é o Kong API Gateway https://docs.konghq.com
3. Faça o deploy do Kong API Gateway
4. Configure uma rota no Kong API Gateway para quando fizermos uma request com o path /desafio, a requisição seja enviada ao app
5. Essa API será pública, mas terá autenticação via chave, crie uma autenticação via Key-Auth no Kong API Gateway

## Entregáveis:
Como entregáveis esperamos um arquivo Dockerfile, um arquivo para subir os containers (docker-compose ou docker-stack ou deployment k8s), um script (python ou shell) com as chamadas para a criação de uma API e um README.md explicando como tudo isso funciona.

## Você ganha pontos extras se:
Se fizer um script que automatize todo esse processo ou faça alguma mudança no app.
Se fizer melhorias no código, como melhrorias entendendemos desde refatorar o código, até criar uma interface web mais bonita.
Se fizer monitoração.
