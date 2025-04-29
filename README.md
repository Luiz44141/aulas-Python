# aulas-Python
(![image](https://github.com/user-attachments/assets/1f8ac47e-b61d-45a2-9d83-67757875d482)

## tipos primitvos: string, number(int/float), boolean
- Para saber mais, [clique aqui.](https://dev.to/dormin/tipos-primitivos-em-python-10jg).
### opeeradores aritméticos
#### operadores lógicos/comparativos
### (if/elif/else)

- **Tipos de estruturas** **_condicionais_**

- if: Executa um bloco de código se uma condição especificada for verdadeira.
- elif: Significa "else if" e permite que você verifique várias condições.
- else: Executa um bloco de código se nenhuma das condições anteriores for verdadeira.
```py
resposta = input("Escreva sua senha: ")
erros = []
if not resposta.isdigit():
  print("Senha fraca: deve conter número")


if not len(resposta) >= 8:
    print("Senha fraca: deve conter no mínimo 8 caracteres")
    if not resposta.lower():
      print("Senha fraca: deve conter letras maiúsculas")
      if not resposta.upper():
        print("Senha fraca: deve conter letras minúsculas")    
    ```
