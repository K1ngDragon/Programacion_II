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
    numero = float(input(f"Ingrese un número (le queda {10-x} ingreso): "))
    if numero > 0:
        print(f"El número positivo ingresado es: {numero}")
print("Fin del programa...")
