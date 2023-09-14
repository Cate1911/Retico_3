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
Paso 3. Eliminar de la lista todos los números (≠i) que terminen en 0, 2, 4, 6 y 8.
Paso 4. Sumar todas las cifras del número siguiente a b hasta que su resultado quede expresado en 1 cifra.
 Si ese resultado es igual a 3, 6 o 9 entonces
  eliminar ese número de la lista
 sino
  repetir el Paso 4 con el siguiente número en la lista
Paso 5. Eliminar de la lista todos los números (≠b) que terminen en 5
Paso 6. Eliminar de la lista todos los números (≠11) que tengan el mismo dígito en todas sus cifras
Paso 7. Elevar al cuadrado el primer número de la lista
 Si el cuadrado de este número se encuentra en la lista
  eliminar el cuadrado de ese número y repetir el Paso 7 con el siguiente número de la lista 
 sino
  escribir ("los números primos que hay desde i hasta n son: (mencionar los números que quedaron en la lista)")
fin
  

