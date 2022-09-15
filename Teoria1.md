# Introdução a Python

## Primeiros Passos

 - Entradas : Usuario interagindo com o programa
 - Saídas : Informações mostradas para o usuario

### Saída mais comum: print

```python
print('FRASE') # PODE DER COM " " OU ''
```

### Formas de comentar um codigo

 - Primeiro: # -> deve ser feito linha por linha
 - Segunda: '''  ''' tudo entre as aspas ficara comentado mesmo que em linhas diferentes

### Forma de entrada mais basica: Input

- Primeiro tipos de variaveis:
   - String(str) - Usado para compor frases
   - Integer(int) - Numero inteiro
   - Float(f) -  Numero com virgula
   - Boolean(bool) -  True or False
- obs: o input sempre armazena como str.Logo é necessario fazer conversao para inteiro

```python

a = int(input('Entre com o valor\n'))
b = int(input())

print(a+b)
```

### Usando Format para saidas 

```python
a = input("insira seu nome\n")
b = int(input("insira sua idade\n"))
print(f'O nome do candidato é: {a} e te tem  {b} anos')
```

### Curiosidades do Print

#### Código
```python
a = input("insira seu nome\n")
b = int(input("insira sua idade\n"))
print(a,b,sep=' - ',end=' Python')
```

#### Saída

```txt
insira seu nome
Thiago
insira sua idade
18
Thiago - 18 Python 
```

