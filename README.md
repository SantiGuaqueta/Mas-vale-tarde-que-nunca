# Mas vale tarde que nunca
Hola mis programadores, o mi profesor:sweat_smile:	 cualquiera que lea este repositorio espero que esten bien, hoy toca realizar el reto 5 propuesto en esta clase [Clase](https://github.com/fegonzalez7/pdc_unal_clase7)  (posdata den estrellita al repositorio del profesor es super importante) se supone que tocaba entregarlo la semana pasada pero lo bueno se hace esperar asi que comencemos :imp: .
## Primer punto
1.Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
Para la realizacion de este punto necesitamos la tabla que corresponde a los codigos ASCII que es la siguiente:
<div align='center'>
<figure> <img src="https://i.postimg.cc/7hH1sGJ1/image.png" alt="" width="600" height="auto"/></br>
<figcaption><b>Tabla de caracteres con equivalente en ASCII.</b></figcaption></figure>
</div>

```python
x=int(input("Escriba un numero="))
print("El número corresponde al código ASCII de una vocal minúscula.")
# Revisamos la tabla para poner las condiciones correctas
if x==97 or x==101 or x== 105 or x== 111 or x==117:
    print("Sí")
else:
    print("No")
# Si funciona bailamos
# Si no funciona reimos para no llorar 
```
[![Captura-de-pantalla-2023-03-11-152140.png](https://i.postimg.cc/VsxGbn8f/Captura-de-pantalla-2023-03-11-152140.png)](https://postimg.cc/t7ztK1Jw)
## Segundo punto
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```python
C=input("Ingrese una cadena de longitud 1 =")
numero_ascii= ord (C)

if numero_ascii % 2 == 0 :
    print("El numero ascii de la primera letra es par")
else:
    print("El numero ascii de la primera letra es impar")
```
[![Captura-de-pantalla-2023-03-11-153959.png](https://i.postimg.cc/3wWprfWt/Captura-de-pantalla-2023-03-11-153959.png)](https://postimg.cc/KKS4JNPT)
### Tercer punto
Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.
``` python
b=input("Ingrese un solo carácter")
ord(b)
x=ord(b)
if x>57 or x<48:
    print("el carácter "+str(b)+" no es un dígito ")
else :
    print("el carácter "+str(b)+" es un dígito ")
```
[![Captura-de-pantalla-2023-03-11-154910.png](https://i.postimg.cc/tJFvS4jn/Captura-de-pantalla-2023-03-11-154910.png)](https://postimg.cc/n9c1MZMn)
#### Cuarto punto
Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"
``` python
x=float(input("Escriba un numero="))

if x>0 :
    print("El numero es positivo") 
elif x<0:
    print( "El número x es negativo")
else:
    print( "El número x es el neutro para la suma")
```
[![Captura-de-pantalla-2023-03-11-155033.png](https://i.postimg.cc/xTRtc7TQ/Captura-de-pantalla-2023-03-11-155033.png)](https://postimg.cc/bsZQ5mtV)
##### Quinto punto
Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
```python 
x = float (input("Ingrese la coordenada en x del centro del circulo: "))
y = float (input("Ingrese la coordenada en y del centro del circulo: "))
radio = float(input("Ingrese el radio del circulo: "))
a = float (input("Ingrese la coodenada en x del punto R2: "))
b = float (input("Ingrese la coordenada en y del punto R2 : "))
if((a-x)**2 + (b-y)**2 <= radio**2):
    print ("El punto en R2 " + str(a) + ", " + str(b) + " pertenece al interior del circulo ")
else: 
    print ("El punto en R2 " + str(a) + ", " + str(b) + " no pertenece al interior del circulo ")
```
[![Captura-de-pantalla-2023-03-11-155125.png](https://i.postimg.cc/bN39zt3N/Captura-de-pantalla-2023-03-11-155125.png)](https://postimg.cc/3d0v1WsP)
###### Sexto punto
Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
``` python
x=float(input("Escriba una longitud="))
y=float(input("Escriba una longitud="))
z=float(input("Escriba una longitud="))

print("Con las longitudes dadas se puede crear un triangulo=")
if x+y>z and x+z>y and z+y>x:
    print("Sí")
else:
    print("No")
```
[![Captura-de-pantalla-2023-03-11-155252.png](https://i.postimg.cc/QMkt3pJf/Captura-de-pantalla-2023-03-11-155252.png)](https://postimg.cc/CZ5YCnt8)
### Fin
