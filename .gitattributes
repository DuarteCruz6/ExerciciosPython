
print("exercicio 1")

num1 = int(input("escolha o número: "))

for i in range(1,num1+1): print(i,end = " ")

print("\n----------------------------------------------------------")
print("exercicio 2")

num2 = float(input("escolha o número: "))
frase = f"{num2} está contido no intervalo "
if num2 < 0:
    print(f"O número {num2} está fora do intervalo")
elif num2 <= 25:
    print(f"{frase} [0,25]")
elif num2 <= 50:
    print(f"{frase} (25,50]")
elif num2 <= 75:
    print(f"{frase} (50,75]")
elif num2<= 100:
    print(f"{frase} (75,100]")
else:
    print("Fora de intervalo")

print("----------------------------------------------------------")
print("exercicio 3")

import math
num3 =int(input("raio do círculo: "))
raioaoquadrado = num3 **2
area = math.pi * raioaoquadrado
print(area)

print("----------------------------------------------------------")
print("exercicio 4")
numero1 = int(input("numero inteiro: "))
numero2 = int(input("numero inteiro: "))
numero3 = float(input("numero real: "))
numero1dobro = 2 * numero1
numero2metade = numero2 / 2
numero1triplo = 3 * numero1
print(numero1dobro * numero2metade)
print(numero1triplo + numero3)
print(numero3 **3)

print("----------------------------------------------------------")
print("exercicio 5")

a = input("vc mora perto da vitima? "),input("ja trabalhou com a vitima? "),input("telefonou para a vitima? "),input("esteve no local do crime? "),input ("devia para a vitima? ")

totalsims= 0
b = 0
while True:
    for i in a:
        if i == "s":
            totalsims += 1
            b += 1
        else:
            totalsims += 0
            b += 1
    if b == 5:
        break
    
def respostas():
    global totalsims
    if totalsims == 5:
            print("assassino")
    elif totalsims in range (3,5):
            print("cumplice")
    elif totalsims == 2:
            print("suspeito")
    elif totalsims in range (0,2):
            print("liberado")
    else:
            print("erro")

respostas()

print("----------------------------------------------------------")
print( "exercicio 6")

lista = input("escreva os números separados por virgula ou espaço: ")

if not "," in lista:
    lista = lista.replace(" ","#")
lista = (lista.replace (",","#"))

lista1 = list(lista.split("#"))

soma = 0
for i in lista1:
    soma += int(i)

print(f"soma: {soma}")

print("----------------------------------------------------------")
print( "exercicio 7")

import math

ponto1 = input("indique as coordenadas do ponto 1 com os valores de x e y separados por 1 virgula ou espaco: ")
ponto2 = input("indique as coordenadas do ponto 2 com os valores de x e y separados por 1 virgula ou espaco: ")

a = list(ponto1.replace(",",""))
if not "," in ponto1:
    a = list(ponto1.replace(" ",""))

b = list(ponto2.replace(",",""))
if not "," in ponto2:
    b = list(ponto2.replace(" ",""))

x1 = float(a[0])
y1 = float(a[1])

x2 = float(b[0])
y2 = float(b[1])

dist = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)

print(f"distancia: {dist}")

print("----------------------------------------------------------")
print( "exercicio 8")
import time

soma = 1
for i in range (1,1001):
    fact = i*soma
    soma = fact

print(f"fatorial do numero 1000: {time.sleep(1)} {soma}")
    
print("----------------------------------------------------------")
print( "exercicio 9")

import random
import time

time.sleep(1)

lista = []

while True:
    i = str(random.randint(1,100))
    lista.append(i)
    if lista.index(i) != 9:
         continue
    else:
         break

print(lista)
lista1 = []
lista2 = []
lista3 = []
lista4 = []

for i in range(0,10):
    if i <=3 :
        lista1.append(lista[i])

    if i > 4:
        lista2.append(lista[i])

    if i%2 == 0:
        lista4.append(lista[i])
    else:
        lista3.append(lista[i])

print(f"lista com os 4 primeiros números: {lista1}")
print(f"lista com os 5 ultimos numeros: {lista2}")
print(f"lista dos elementos nas posicoes pares: {lista3}")
print(f"lista dos elementos nas posicoes impares: {lista4}")

lista5 = lista[::-1]
lista1.append(str(lista[4]))
lista6 = lista1[::-1]
lista7 = lista2[::-1]

print(f"lista original invertida: {lista5}")
print(f"lista inversa dos 5 primeiros numeros: {lista6}")
print(f"lista inversa dos 5 ultimos numeros: {lista7}")

print("----------------------------------------------------------")
print( "exercicio 10")

duracao = {"W": 1,
           "H":0.5,
           "Q":0.25,
           "E":1/8,
           "S":1/16,
           "T":1/32,
           "X":1/64
          }

while True:
    original = input("Composição: ").upper()

    comp = original.replace("/","#")
    comp1 = comp.replace("#","",1)
    comp2 = comp1[::-1]
    comp3 = comp2.replace("#","",1)
    comp = comp3[::-1]
    comp = comp.split("#")

    certos = 0
    incorretos = ""
    for i in comp:
        tempo= 0
        a=0
        while True:
                try:
                    j = i[a]
                    tempo += duracao[j]
                    a += 1
                except: 
                    break

        if tempo == 1:
            certos +=1
        else: 
            incorretos += (f"{str(i)},")

    if incorretos == "":
        incorretos = "Nenhum"
    else:
        incorretos = incorretos [::-1]
        incorretos = incorretos.replace(",","",1)
        incorretos = incorretos[::-1]

    print(f"Qtd. de corretos: {certos}\nIncorretos: {str(incorretos)}")
    refazer = input("Quer fazer dnv (s/n)? ").lower()
    if refazer == "n":
        break
