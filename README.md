# Reto número 4 repo
### Fecha:  11-09-2023
**1.** Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
* EXPLICACIÓN
* Mirar archivo Punto_1.ipynb
```pseudocode
print("-------------------------------------------------------")
print("Determinar si el número n corresponde al código ASCII de una vocal minúscula")
print("-------------------------------------------------------")
#Entradas
n: int = 0
print("Ingrese un número: ")
n=int( input("n: "))
#Proceso
if (97<=n<=122):
  print("-------------------------------------------------------")
  print("El número ingresado corresponde a una vocal minúscula")
  if n==97 :
    print("Corresponde a la letra a")
  elif n==101 :
    print("Corresponde a la letra e")
  elif n==105 :
    print("Corresponde a la letra i")
  elif n==111 :
    print("Corresponde a la letra o")
  elif n==117 :
    print("Corresponde a la letra u")
else:
  print("-------------------------------------------------------")
  print("El número ingresado NO corresponde a una vocal minúscula")
```
**2.** Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
* EXPLICACIÓN
* Mirar archivo Punto_2.ipynb
```pseudocode
print("-------------------------------------------------------")
print("Determinar si la primera letra de una cadena de longitud 1 corresponde a un número par o impar del código ASCII")
print("-------------------------------------------------------")
#Entradas
#Entradas
letras: str
primera_letra: str
letra_mayu: str
p: str
print("Ingrese una palabra: ")
p=str( input("p: "))
#Proceso
letras = p.split(" ")
primera_letra=""
for word in letras:
  primera_letra += word[0]
  letra_mayu=primera_letra.upper()
  print(letra_mayu)

if letra_mayu=="B" or letra_mayu=="D" or letra_mayu=="F" or letra_mayu=="H" or letra_mayu=="J" or letra_mayu=="L" or letra_mayu=="N" or letra_mayu=="P" or letra_mayu=="R" or letra_mayu=="T" or letra_mayu=="V" or letra_mayu=="X" or letra_mayu=="Z":
  print("El número correspondiente en el código ASCII es par")
else:
   print("El número correspondiente en el código ASCII es impar")
```
**3.** Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
* EXPLICACIÓN
* Mirar archivo Punto_3.ipynb
```pseudocode
print("-------------------------------------------------------")
print("Determinar si un carácter es dígito o no")
print("-------------------------------------------------------")
#Entradas
c: float = 0.0
print("Ingrese un caracter: ")
c=input("c:")
type(c)
#Proceso
if (c>="0" and c<="9"):
    print("El carácter ingresado SI es un dígito")
else:
    print("El carácter ingresado NO es un dígito")
```
**4.** Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación: Positivo: "El número x es positivo"; Negativo: "El número x es negativo"; Cero (0): "El número x es el neutro para la suma"
* EXPLICACIÓN
* Mirar archivo Punto_4.ipynb
```pseudocode
print("-------------------------------------------------------")
print("Determinar si el número es positivo, negativo o cero")
print("-------------------------------------------------------")
#Entradas
x: int
print("Ingrese un número: ")
x=int( input("x: "))
#Proceso
if x>0:
  print("El número x es positivo")
elif x<0:
  print("El número x es negativo")
else:
  print("El número x es el neutro para la suma")
```
**5.** Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
* EXPLICACIÓN
* Mirar archivo Punto_5.ipynb
```pseudocode
print("-------------------------------------------------------")
print("Determinar si un punto R2 pertenece al interior del círculo")
print("-------------------------------------------------------")
#Entradas
centro=[]
radio=[]
R2=[]
print("Ingrese el centro del círculo coordenada en eje X: ")
cx=int( input("cx: "))
print("Ingrese el centro del círculo coordenada en eje Y: ")
cy=int( input("cy: "))
centro.append(cx)
centro.append(cy)
print("Ingrese el radio del círculo: ")
r=int( input("r: "))
radio.append(r)
print("Ingrese coordenada en eje X del punto R2: ")
R2x=int( input("R2x: "))
print("Ingrese coordenada en eje Y del punto R2: ")
R2y=int( input("R2y: "))
R2.append(R2x)
R2.append(R2y)
print(f"Coordenadas del centro: {centro}")
print(f"Coordenadas del radio: {radio}")
print(f"Coordenadas punto R2: {R2}")
#Proceso
ecuacion1=((R2x-cx)**2) + ((R2y-cy)**2)
ecuacion2=(r**2)
if ecuacion1==ecuacion2:
  print("R2 SI pertenece al interior del círculo")
else:
  print("R2 NO pertenece al interior del círculo")
```
**6.** Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
* EXPLICACIÓN
* Mirar archivo Punto_6.ipynb
```pseudocode
print("-------------------------------------------------------")
print("Determinar si con tres longitudes dadas se puede contruir un triángulo")
print("-------------------------------------------------------")
#Entradas
L1: float = 0
L2: float = 0
L3: float = 0
print("Ingrese 3 longitudes")
L1=input("L1: ")
L2=input("L2: ")
L3=input("L3: ")
#Proceso
if (L1+L2)>L3:
  print("SI se puede formar un triángulo con las medidas ingresadas")
else: 
  print("NO se puede formar un triángulo con las medidas ingresadas")
```
