# 🧪 Cenários de Teste - Login

## Cenário 1: Login com sucesso
Dado que o usuário está na tela de login  
Quando informar email e senha válidos  
Então o sistema deve permitir o acesso  

## Cenário 2: Senha inválida
Dado que o usuário está na tela de login  
Quando informar senha incorreta  
Então deve exibir mensagem de erro  

## Cenário 3: Campos vazios
Dado que o usuário está na tela de login  
Quando não preencher os campos  
Então o sistema deve impedir o login  

## Cenário 4: Email inválido
Dado que o usuário está na tela de login  
Quando informar um email inválido  
Então deve exibir mensagem de erro  

## Cenário 5: Caracteres especiais
Dado que o usuário está na tela de login  
Quando inserir caracteres especiais no campo email  
Então o sistema deve validar corretamente  