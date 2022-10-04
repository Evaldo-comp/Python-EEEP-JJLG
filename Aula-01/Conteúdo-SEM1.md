## Saída de dados

Para imprimir dados na tela , nós utilizaremos o comando `print()`, dentro do parênteses iremos iinserir a mensagem ou outro dado que queremos mostrar ao usuário, se
quisermos mostrar um texto, este texto deverá ser inserido dentro do parênteses entre aspas, podendo ser simples ou duplas.

`print("Olá Mundo!!!)`

## Declaração de variáveis

Python é uma linguagem muito simples e direta, um exemplo dessa simplicidade pode ser observado na declaração de variáveis. Em algumas linguagens as variáveis são 
fortemente tipadas, a declaração de uma variável deve ser composta pelo tipo de dado que aquela variável irá guardar e o nome da variável. Já em Paython isso não 
é necessário pois a linguagem reconhece o tipo de dado no momento que essa variável é preenchida, sendo assim, sua declaração precisará apenas no nome da mesma.

` idade = 25 `

---

## Operadores Relacionais

|Operador|Operação|Símbolo Matemático|
|--------|---------|-----------------|
|    ==  |Igualdade|       =         |
|   >    | maior que|      >         |
|   <    |menor que|       <         |
|   !=   | diferente|      #         |
|   >=   | maior ou igual|   >=     |
|   <=    | menor ou igual|   <=     |

Ao realizar-mos a camparação de dados utilizando operadores relacionais, obteremos outro tipo de dado chamado Booleano (True ou False).

---

## Formatação da saída de strings
 As versões mais recentes de Python melhoram bastante o estilo de formação da saida de dados cocatenados e inseridos dentro de uma string. Basta seguir o exemplo.
 
 ```
 # Format strings

nome = "Evaldo"
idade = 23
Altura = 1.75

print(f"Olá {nome} você tem  {idade} anos e mede {Altura}")
```
---

## Entrada de dados

Para receber dados do usuário, iremos utilizar a função `input()` que receberá como parâmetro a informação fornecida pelo usuário, essa informação por sua vez
pode ser utilizada em um determinado processamento ou ser amrazenda em uma variável.

```
# Entrada de dados

nome = input("Digite seu nome\n")
print(f"Olá {nome}, tudo bem?")
```
A função input por padrão sempre retorna strings, caso seja necessário receber um número de um usuário, será necessario converter o dado recebido .
```
# Conversão de string

idade = int(input("Digite sua idade\n"))
altura = float(input("Digite sua altura\n"))
nome = input("Digite seu nome\n")
print(f"Olá {nome}, tudo bem?, você tem {idade} e {altura} de altura")
```
