# Exercicios avancados 
Questões de programação
Questão 1 

1 - Escreva um algoritmo que armazene o valor 10 em uma variável A e o valor 20 em uma variável B. A seguir (utilizando apenas atribuições entre variáveis) troque os seus conteúdos fazendo com que o valor que está em A passe para B e vice-versa. Ao final, escrever os valores que ficaram armazenados nas va

A = 10
B = 20
 Utilizando uma variável auxiliar para a troca
temp = A
A = B
B = temp
print("Valor de A:", A)
print("Valor de B:", B)

2-Escreva um algoritmo para ler um valor (do teclado) e escrever (na tela) o seu antecessor

valor = int(input("Digite um valor: "))
Calculando o antecessor
antecessor = valor - 1
Exibindo o antecessor
print("O antecessor de é", valor, "é", antecessor)
resolução: 
Valor=int(input(''digite algo''))
antecessor=valor-1
print('' o antecessor de '', valor, ''é'', antecessor)

6) Escreva um algoritmo para ler as dimensões de um retângulo (base e altura), calcular e escrever a área do retângulo
 altura = inteiro
base = inteiro
area = inteiro

inicio
  escreva("Digite a altura do retângulo: ")
  leia(altura)
  escreva("Digite a base do retângulo: ")
  leia(base)
  area <- altura * base
  escreval("A área do retângulo é: ", area , "m²")

  
altura = int( input() )
print("diga a base")
base = input()
print()
area = input()



 7)Faça um algoritmo que leia a idade de uma pessoa expressa em anos, meses e dias e escreva a idade dessa pessoa expressa apenas em dias. Considerar ano com 365 dias e mês com 30 dias.
 Resolução: O algoritmo precisa considerar o número de dias em cada mês e também se o ano é bissexto para calcular a idade total em dias corretamente.
