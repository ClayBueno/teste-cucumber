# teste-cucumber

Automação que acessa a página https://demo.applitools.com/index.html e realiza um teste básico de login que verifica se o usuário consegue
logar com sucesso!

### Instalar as dependências:
 ```  npm install```

### Rodar o código:
``` npm test```

### Caso de sucesso:
Caso o login tenha sido realizado com sucesso o sistema exibirá a seguinte mensagem:
```
.
ACME demo app
true
.

1 scenario (1 passed)
4 steps (4 passed)
```

### Caso de falha:
Para simular uma falha no login basta acessar o arquivo: login.feature e modificar o nome da página
