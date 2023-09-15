# Retico_3
## Algoritmo para plantear números primos hasta n
* **_Con Github_**  
```pseudocode
Algoritmo números primos hasta n
n : entero
i : entero
a : entero
b : entero
c : entero
inicio
i := 2
a := 3
b := 5
c := 11
Paso 1. Ingrese un número entero (n)
Paso 2. Cree una lista de números desde i hasta n
Paso 3. Eliminar de la lista todos los números (≠i) que terminen en 0, 2, 4, 6 y 8
Paso 4. Sumar todas las cifras del número siguiente a b hasta que su resultado quede expresado en 1 cifra
 Si ese resultado es igual a 3, 6 o 9 entonces
  eliminar ese número de la lista
 sino
  repetir el Paso 4 con el siguiente número en la lista
Paso 5. Eliminar de la lista todos los números (≠b) que terminen en 5
Paso 6. Eliminar de la lista todos los números (≠11) que tengan el mismo dígito en todas sus cifras
Paso 7. Elevar al cuadrado el primer número de la lista
 Si el cuadrado de este número se encuentra en la lista entonces
  eliminar el cuadrado de ese número y repetir el Paso 7 con el siguiente número de la lista 
 sino
  escribir ("los números primos que hay desde i hasta n son: (mencionar los números que quedaron en la lista)")
fin
```
* **_Con Diagrama de Flujo_**

## Algoritmo para hallar la raíz cuadrada de cualquier número real
```pseudocode
Algoritmo raíz cuadrada de cualquier número real
n : real (R)
inicio
n >= 0
Paso 1. Ingrese un número (n)
 Si n es 0
  escribir ("La raíz cuadrada de 0 es 0")
 sino
  realizar el Paso 2
Paso 2. dividir n entre 2 y escribir el 2 a un lado
 Mientras ese resultado termine en los dígitos 0, 2, 4, 6 u 8 hacer
  Si ese resultado da un número que termina en los dígitos 0, 2,4, 6 u 8 entonces
   dividir ese resultado entre 2, escribir el 2 a un lado y repetir el Paso 2 con el resultado que le dió.
  sino
   continuar con el paso 3
Paso 3.  dividir ese resultado entre 3 y escribir el 3 a un lado
 Mientras ese resultado dé como residuo de su división 0 hacer
  Si ese resultado tiene como residuo de su división 0 entonces
   dividir ese resultado entre 3, escribir el 3 a un lado y repetir el Paso 3 con el resultado que le dió.
  sino
   continuar con el paso 4
Paso 4. dividir ese resultado entre 5 y escribir el 5 a un lado
 Mientras ese resultado dé como residuo de su división 0 hacer
  Si ese resultado tiene como residuo de su división 0 entonces
   dividir ese resultado entre 5, escribir el 5 a un lado y repetir el Paso 4 con el resultado que le dió.
  sino
   continuar con el paso 5
Paso 5. dividir ese resultado entre 5 y escribir el 7 a un lado
 Mientras ese resultado dé como residuo de su división 0 hacer
  Si ese resultado tiene como residuo de su división 0 entonces
   dividir ese resultado entre 7, escribir el 7 a un lado y repetir el Paso 5 con el resultado que le dió.
  sino
   continuar con el paso 6
Paso 6. dividir ese resultado entre 11 y escribir el 11 a un lado
 Mientras ese resultado dé como residuo de su división 0 hacer
  Si ese resultado tiene como residuo de su división 0 entonces
   dividir ese resultado entre 11, escribir el 11 a un lado y repetir el Paso 6 con el resultado que le dió.
  sino
   continuar con el paso 7
Paso 7. dividir ese resultado entre 13 y escribir el 13 a un lado
 Mientras ese resultado dé como residuo de su división 0 hacer
  Si ese resultado tiene como residuo de su división 0 entonces
   dividir ese resultado entre 13, escribir el 13 a un lado y repetir el Paso 7 con el resultado que le dió.
  sino
   continuar con el paso 8.
Paso 8. 
 Si tiene algún  número escrito a un lado entonces
  Cuente cuántos números de los que escribió a un lado son iguales (cuántos 2, cuántos 3, cuántos 5, cuántos 7, cuántos 11 y cuántos 13 hay)
sino
  escribir ("La raíz cuadrada de n no es exacta, entonces, se podría expresar como √n)
Paso 9. Agrupe los números en parejas del mismo número (por ejemplo, si hay 4 números 3, entonces agrupe los números 3 en 2 parejas conformadas por dos 3 en cada caso)
 Si hay números que se quedan sin pareja o sin agrupar entonces
  Dejarlos expresados como la raíz cuadrada de estos
 sino
  Reescribir cada pareja como el cuadrado de ese número (Ej: 2 y 2=2^2)
Paso 10. Sacarle raíz cuadrada a cada pareja reescrita, cancelando la raíz cuadrada con el cuadrado de la pareja.
Paso 11. Multiplicar todos los resultados, incluyendo los números que quedaron expresados en forma de raíces en el Paso 9 (en caso de que haya).
Paso 11. Escribir ("La raíz cuadrada de n es igual a: (inserte el resultado del procedimiento anteriormente realizado)")
fin
```

