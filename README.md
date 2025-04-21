![ ](FACEN.png)

> [!NOTE]
>:man_student: _**Alumno:**_ _Mario Jorge Tapia_ <br/> :memo: _**M.U. Nº**_: _601 (Redes)_


## Trabajos prácticos de la Cátedra, Programación II Trabajo Práctico:<br/>Estructura `For` y función `Range` en Python
---
### Resolver los siguientes ejercicios en Python utilizando la sentencia for

1. Imprimir los años del 1945 al 2025. :heavy_check_mark:

```python
for x in range (1945, 2025+1):
    print(f"El año que se impripe es: {x}")''
```
2. Imprimir los números pares del 2 al 200. :heavy_check_mark:

```python
for x in range (2, 200+1,2):
   print(f"El año que se impripe es: {x}")
```    

3. Mostrar los números del 100 al 14 en orden descendente. :heavy_check_mark:

```python
for x in range (100, 14-1, -1):
  print(f"El número en forma descendente es: {x}")
```
4. Imprimir la tabla de multiplicar del 5. :heavy_check_mark:
```python
for x in range (0, 10):
   multiplo = x + 1
   print(f"5 x {multiplo} = {5 * multiplo}")
```
5. Imprimir los primeros 100 números en la escala del 3. :heavy_check_mark:

```python
for x in range (1, 101):
    resultado = x * 3
    print(f"Los 100 primeros 100 números son = {resultado}")
```
6. Sumar todos los números del 1 al 100 e imprimir el resultado. :heavy_check_mark:

```python
for x in range (0, 101):
    suma= x + 1
    suma_total = suma_total + suma
print (f"La suma total de los 100 primeros números es {suma_total}")
```
7. Pedir al Usuario un número y mostrarlo solo en caso que sea positivo. Repita 10 veces :heavy_check_mark:
```python
for x in range(10):
    numero = float(input(f"Ingrese un número (le queda/n {10-x} ingreso/s): "))
    if numero > 0:
        print(f"El número positivo ingresado es: {numero}")
print("Fin del programa...")
```
8. Pedir al Usuario una palabra. Luego mostrarla letra por letra
```python
frase = input("Introduce una palabra o frase: ")

for i in frase:
    print(i)
```
.-Extra
```python
frase = input("Introduce una palabra o frase: ")

a = 0
e = 0
i = 0
o = 0
u = 0
á = 0
é = 0
í = 0
ó = 0
ú = 0

frase = frase.lower()

for caracter in frase:
    if caracter == 'a':
        a += 1
    elif caracter == 'e':
        e += 1
    elif caracter == 'i':
        i += 1
    elif caracter == 'o':
        o += 1
    elif caracter == 'u':
        u += 1
    elif caracter == 'u':
        á += 1
    elif caracter == 'e':
        é += 1
    elif caracter == 'i':
        í += 1
    elif caracter == 'o':
        ó += 1
    elif caracter == 'u':
        ú += 1

print("\nConteo de vocales:")
print(f"a = {a}")
print(f"e = {e}")
print(f"i = {i}")
print(f"o = {o}")
print(f"u = {u}")
print(f"á = {á}")
print(f"é = {é}")
print(f"í = {í}")
print(f"ó = {ó}")
print(f"ú = {ú}")

# Imprimir el total de vocales
total_vocales = a + e + i + o + u + á + é + í + ó + ú
print(f"\nTotal de vocales: {total_vocales}")
```
