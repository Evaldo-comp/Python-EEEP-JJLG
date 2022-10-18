



#  Condicionais

- Condicionais
  - If
  - else
  - Aninhados
  - elif

---

## Condicionais:

As condicionais são estruturas que servem para tomar decisões com base em algum teste, que por sua vez retorna um valor booleano Verdadeiro ou Falso. A estrutura básica de uma condicional é a seguinte:
```
if <condição>:
       bloco verdadeiro executado
```
Um conteúdo para estar dentro de uma condição, deve estar identado de forma que todas as sentença estejam dentro desse bloco, ou seja, 4 espaços recuados à direita.

```
if <condição>:
       bloco verdadeiro executado # trecho dentro do if
bloco extra  # trecho fora do if
```



**Exemplos:**
```python
a = 1
if a > 2:
  print("A é maior do que dois")


if a % 2 == 0 :
  print("a é par")
```

**Short Hand if:** É uma forma de utilizar o `if` apenas em linha única, isso pode optimizar a leitura, mas não é indicado se você está aprendendo a linguagem agora.
```python
idade = 18
if idade >=18: print("Maior de idade")
```
----

## If..else:

Para que o programa responda a uma codicional falsa, acrescente a clausula **else**  após o if:
```python
if<condição>:
      bloco verdadeiro
else:
      bloco falso

```
**Exemplo:**
```python
b = 2
if b % 2 == 0 :
  print("b é par")
else:
  print("b é impar")
```

**Short Hand if..else:** A estrutura de `If...else` também tem sua versão de linha única.
```python
idade = 17
print("Maior de idade")  if idade >=18 else print("Menor de idade")
```
---

## Expressões aninhadas:
Também é possível colocar um if dentro de outro if, e um else dentro deste, esse agrupamento é o que chamados de estrutura **aninhada**:


**Exemplo:** 
```python
num = int(input("Número: \n"))

if (num > 0):
  print(f'{num} é positivo')
else:
   if (num < 0):
      print(f"{num} é negativo\n")
   else:
     print(f"{num} é igual a 0\n")
```

## elif:
Podemos simplificar a escrita de estruturas aninhadas utilizando o **elif**


**Exemplo:**
```python
num = int(input("Número: \n"))

if (num > 0):
  print(f'{num} é positivo')
elif (num < 0):
      print(f"{num} é negativo\n")
else:
     print(f"{num} é igual a 0\n")
```
---


---

:house:[Home](https://github.com/Evaldo-comp/Python-EEEP-JJLG)

---

