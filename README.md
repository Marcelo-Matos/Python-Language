# Python-Language

Practicing Exercises - You tube "Cursos em Vídeo" with Gustavo Guanabara
_______________________
Exercise 000
print('Olá Mundo!!')

_______________________

Exercise 001
nome=input('Qual seu nome?')
print('Bem vindo,', nome, '!')

_______________________

Exercise 002
nome=input('Digite seu nome: ')
print('Olá, ',(nome),'prazer te conhecer!')

nome=input('Olá, digite seu nome e tecle ENTER em seguida:')
print('Seja bem-vindo, {}!'.format(nome))

__________________________

Exercise 003
n1=int(input('Digite um numero:'))
n2=int(input('Digite mais um numero: '))
s=n1+n2
print('A soma vale',s)

n1=int(input('Digite um numero:'))
n2=int(input('Digite mais um numero: '))
s=n1+n2
print('A soma vale: {}'.format(s))

__________________________

Exercise 003a
n1=int(input('Digite um valor: '))
n2=int(input('Digite mais um numero: '))
s=n1+n2

print('A soma entre {} e {} vale {}'.format(n1, n2, s))

#print('A soma entre', n1, 'e', n2, 'vale', s)

#print('A soma vale: ', s)

___________________________

Exercise 003b
n1=int(input('Digite um numero: '))
n2=int(input('Digite mais um numero: '))
s=n1+n2
print('A soma entre {} e {} é {}'.format(n1, n2, s))
print(type(n1))

n1=input('Digite um numero: ')
n2=input('Digite outro número ou alfanumero: ')
print(n1.isnumeric())
print(n2.isupper())
print(n2.isalnum())
print(type(n1))
print(type(n2))

# Operadores aritimeticos
# + : Soma
# - : Subtração
# / : Multiplicação
# ** : Potencia
# // : Divisão Inteira
# % : Resto da Divisão

_______________________

Challenge 003 b

n =(input('Digite um valor: '))
print(n.isalnum())

print(n.isupper())

print(n.isalpha())

print(n.isnumeric())


#n =int(input('Digite um valor'))
#print(type(n))

____________________

Exercise 004 - challenge 5

n1=int(input('Digite um número:'))
dobro=n1**2
triplo=n1**3
raiz=n1/1/2
print('O Dobro deste numero é {:^5}, seu triplo é {:<4} e sua raiz quadrada é {:=^10}'.format(dobro,triplo,raiz))

____________________

Exercise 004 a

#nome = str(input('Qual é seu nome? '))
#print('Prazer em te conhecer{:=^20} !'.format(nome))
n1=int(input('Digite um valor  '))
n2=int(input('Digite outro valor  '))
s=n1+n2
m=n1*n2
d=n1/n2
di=n1//n2
e=n1**n2
r=n1%n2
print('A soma é {}, \n o produto é {} e a \ndivisão é {:.3f}'.format(s, m, d,), end=' >>> ')
print('Divisão Inteira é {}, potencia é {} e resto é {}'. format(di, e, r))


#print('A soma é {}'.format(n1+n2))

____________________

Exercise 005

#Faça um programa que leia um numero inteiro e mostre na tela o seu sucessor e seu antecessor
n1=int(input('Digite um numero:  '))
print("o Antecessor deste número é: {} \n".format(n1-1),end='>>> ')
print('O sucessor deste número é {}'. format(n1+1))

___________________

Exercise 007 - Challenge 007

#Desenvolva um programa que leia as duas notas de um aluno, calcule e mostre sua media

n1=(input('Qual a nota 1 do aluno: '))
n2=(input('Qual a nota 2 do aluno: '))
m=(n1+n2)/2

Print (n1+n2)

#Print('De acordo com as notas do aluno, sendo sua nota 1 {:=10} e sua nota 2 {:>3}, sua média é {:^4} '.format(n1,n2,m))

__________________
Exercise 007 - Challenge 008

#Escreva um programa que leia um valor em metros e o exiba convertido em centimetros e milimetros

m=int(input("Olá, digite um numero (representa metro):  "))
cm=100
mm=1000
cm1=m*cm
mm1=m*mm

print('O valor que você digitou em cm é {:.3f} e em mm é {:.3f}'.format(cm1,mm1)

__________________

Exercise 007 - Challenge 009

n=int(input("Digite um numero:  "))

n1=1
n2=2
n3=3
n4=4
n5=5
n6=6
n7=7
n8=8
n9=9
n10=10

tab1=n*1
tab2=n*2
tab3=n*3
tab4=n*4
tab5=n*5
tab6=n*6
tab7=n*7
tab8=n*8
tab9=n*9
tab10=n*10

print('A tabuada deste número é : \n {} \n {} \n {} \n {} \n {} \n {} \n {} \n {} \n {} \n {}'.format(tab1, tab2, tab3, tab4, tab5, tab6, tab7, tab8, tab9, tab10))

___________________

Exercise 007 - Challenge 10

money=float(input('Para calcular o dólar, quanto você tem na carteira agora? '))
tx=5.30
usd=float(money/tx)

print('Você pode comprar USD {:.4f} com esse dinheiro'.format(usd))

________________




