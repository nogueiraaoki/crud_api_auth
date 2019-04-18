# CRUD API em python + Flask + JWT(auth) + mysql

Modelo de CRUD REST API em python.

modelo baseado em https://github.com/oleg-agapov/flask-jwt-auth


# Para executar o projeto

``` bash
docker-compose build
docker-compose up -d

```

# Para acessar o Modelo

https://localhost

# Rotas
Para criar usuario novo:
![Image description](https://i.imgur.com/W91rG7z.png)

Para adquirir token de acesso:
![Image description](https://i.imgur.com/WF6kGSS.png)

Para listar todos os usuários:
![Image description](https://i.imgur.com/QVEozn3.png)

* próximas ações será preciso do token no header com Authorization: Bearer <token>
Para listar um único usuário:
![Image description](https://i.imgur.com/vIsOqTQ.png)

Para atualizar um usuário:
![Image description](https://i.imgur.com/0BvRqI0.png)

Para excluir um usuário:
![Image description](https://i.imgur.com/kAylJz7.png)
