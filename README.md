# Ret_-5_---
Aquí podrán encontrar los códigos e imágenes que muestran como funcionan los códigos.
## Codigos 
### 1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
Realice el código para que cuando se pase a código ASCII sí es igual a una vocal minuscula.
![image](https://user-images.githubusercontent.com/124615019/222998061-29cc649a-7744-4a4d-b1cc-08f5c30e5a38.png)
Código 
```
x : int
x = int(input("Ponga un número: "))
if chr(x) == "a":
   print(''+ str(x) +' es una vocal minuscula en ASCII que equivale "a"')
elif chr(x) == "e":
   print(''+ str(x) +' es una vocal minuscula en ASCII que equivale "e"')
elif chr(x) == "i":
   print(''+ str(x) +' es una vocal minuscula en ASCII que equivale "i"')
elif chr(x) == "o":
   print(''+ str(x) +' es una vocal minuscula en ASCII que equivale "o"')
elif chr(x) == "u":
   print(''+ str(x) +' es una vocal minuscula en ASCII que equivale "u"')
else:
   print(""+ str(x) +" no es una vocal minuscula en ASCII")
   ```
### 2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
Para saber si era par o impar, dividi por 2, si el residuo me daba 0 era par, sino impar.
![image](https://user-images.githubusercontent.com/124615019/222999024-c4f2ecd6-97e9-40d7-881a-695bb0ad3427.png)
```
x = (input("Ingrese una longitud: "))
u = ord(x)
if u % 2 == 0: 
    print("La longitud "+ str(x) +" es par")
else:
    print("La longitud "+ str(x) +" no es par")
```
### 3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
Para realizar el código tonme del 0 al 9, tome uno por uno, sino coincidia va a dar que no es un digito.
![image](https://user-images.githubusercontent.com/124615019/222999413-a0bcad71-0dcc-4a08-8228-4b0717d76c50.png)
```
x = int(input("Ingrese un caracter: "))
u = chr(x)
if u == "0":
    print("El caracter es un digito")
elif u == "1":
    print("El caracter es un digito")
elif u == "2":
    print("El caracter es un digito")
elif u == "3":
    print("El caracter es un digito")
elif u == "4":
    print("El caracter es un digito")
elif u == "5":
    print("El caracter es un digito")
elif u == "6":
    print("El caracter es un digito")
elif u == "7":
    print("El caracter es un digito")
elif u == "8":
    print("El caracter es un digito")
elif u == "9":
    print("El caracter es un digito")
else:
    print("El caracter no es un digito")
```
### 4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma".
Para este código cada persona ingresa un número real, en el código utilice el mayor, menor o igual, donde los números mayores a 0 son positivos, los menores a 0 negativos y 0 igual a neutro.
![image](https://user-images.githubusercontent.com/124615019/222999860-e20efb3f-cc38-4660-8514-c70bd83ca190.png)
```
x : float
x = float(input("Ingrese un número real: "))
if x > 0:
    print("El número "+ str(x) +" es positivo")
elif x < 0:
    print("El número "+ str(x) +" es negativo")
elif x == 0:
    print("El número "+ str(x) +" es el neutro para la suma")
```
### 5. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
Con los datos que ingresen y el radio, se restaran los puntos en x y los puntos en y, cada uno a la 2, se suman y se compara con el radio para saber sí esos puntos pertenecen o no al circulo
![image](https://user-images.githubusercontent.com/124615019/223000739-86da7244-6873-4f00-a8e0-22c489840b98.png)
```
x : float
y : float
r : float 
p : float
f : float
x = float(input("Ingrese una coordenada para centro del circulo respecto al eje x: "))
y = float(input("Ingrese una coordenada para centro del circulo respecto al eje y: "))
r = float(input("Ingrese el radio: "))
p = float(input("Ingrese una cordenada respecto al eje x: "))
f = float(input("Ingrese una cordenada respecto al eje y: "))

if ((p - x) ** 2 +(f - y) ** 2)<= r :
    print("Las coordenas del punto que ingreso estan dentro del circlulo")
else:
     print("Las coordenas del punto que ingreso no estan dentro del circlulo")
```
### 6. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
Para un triángulo la suma de dos lados debe ser más grandes que el lado restante, sino cumple no se puede formar un triángulo, con está teoría realice el código.
![image](https://user-images.githubusercontent.com/124615019/223001101-aaac4fd8-d772-43a1-afa1-b049245367bc.png)
```
a : float
b : float
c : float
a = float(input("Ingrese la primera longitud: "))
b = float(input("Ingrese la segunda longitud: "))
c = float(input("Ingrese la tercera longitud: "))
if a + b > c and a + c > b and b + c > a : 
    print("Con las longitudes dadas se puede construir un triánguilo")
else:
    print("Con las longitudes dadas no se puede contruir un triángulo")
```
#### !Muchas gracias por su tiempo¡

