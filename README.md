# Ejercicios-python
#Escribir un programa que pregunte al usuario su edad
# y muestre por pantalla si es mayor de edad o no.

edad = int(input('Digite su edad:'))

while edad<0 or edad>100:
   print('Digita una edad valida')
   edad = int(input('Digite su edad:'))
if edad>=18:
     print('El usuario es Mayor de edad')
else: 
     print('El usuario es Menor de edad')  

     
#Escribir un programa que pida al usuario un número entero y
# muestre por pantalla si es par o impar.

num = int(input('Digita un numero entero:'))
while num<0:
    print('Digita un numero entero positivo')
    num = int(input('Digita un numero entero:'))
if num %2 ==0:
    print('El numero',num,'es par')
else:
    print('El numero',num,'es impar')
